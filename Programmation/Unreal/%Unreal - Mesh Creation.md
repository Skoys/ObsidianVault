How to create a Mesh in unreal via blueprints ?
I will explain it from a conceptual point of view and with a Tutorial on how to create a plane for the example.
#### INDEX
  1.  Overview
  2.  Blueprint Creation
  3.  Creating the vertices
  4.  Triangle Calculation
  5.  !Making UVs

-----
#### Overview

See -> [[%Mesh - Basic Overview]]

-------------
#### Creating the Blueprint of the object
To create a mesh, you first need to make a blueprint that will contain it. A normal blueprint will do the job.
In it, you will need to put a ***Procedural Mesh* Component**.

```
> Example / Tutorial:
> Create 2 *integer* variables named:
> - XVertex Count
> - YVertex Count
> And 1 *float* named:
> - Cell Size
> Put in "XVertex Count" default value: 3, in "YVertex" default value: 5 and in "Cell Size" default value: 100 (centimeters).
```

---------------------------------------------
#### Creating the Vertices of the Mesh
You will need to create a **array of *Vector3*** named "**Vertices**" that will contain the coordinates of all the Vertices. Remember:

Number of the vertices -> || (int) array index : <x, y, z> || <- Coordinate of the vertices

```
> Example / Tutorial:
> Add 2 For Loops, 1 for "YVertex Count" - 1 and the other for "XVertex Count" - 1.

> To the second Loop, add to the Body: "Add to Vertices", right click the vector 3 and click on "split structure pin". You should have the x, y and z components separated.
> On:
> X - Put the second loop index multiplied by the cell size 
> Y - Put the first loop index multiplied by the cell size 
> Z - 0

>The vertices are now created.
```

---------------------------------------------
#### Calculating the Faces of the Mesh
Create now an **array of *Integers*** and name it "**Triangles**". In it, you will need to put 3 by 3 ***Vertices* array indexes** to make a triangle.

```
> Example / Tutorial:
> Add 2 For Loops, 1 for "YVertex Count" - 2 and the other for "XVertex Count" - 2.
> Why - 2 instead of - 1? It's because of the way we will make the triangle, we will start by the bottom left one to then get the one on the right and the one on top. If we put - 1, it will try to create a triangle where there is no vertice on the top or the right.

> Now create 3 "Add to Triangles"
> On:
> X - Put the second loop index multiplied by the cell size 
> Y - Put the first loop index multiplied by the cell size 
> Z - 0

>The vertices are now created.
```






Ok a cube is cool and all but we need now to correct some errors, it seems that some faces are not in the orientation we want and the textures are not being placed were we want them to be.

It is because we forgot to create the normals
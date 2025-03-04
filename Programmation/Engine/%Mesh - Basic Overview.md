To create Meshes in Unreal, See -> [[%Unreal - Mesh Creation]]

Here you will find the basic needs of a mesh from points in space
###### Beginner
To create a Mesh in Unreal is nearly the same as creating one in OpenGL. A Mesh like a cube is made with vertices ( points in a 3D space ). 

They are then connected to each other to form triangles. These triangles form a face.

> Example:
> A cube is composed from 6 faces. But the faces are squares and as we said before the faces we want are triangles. We are lucky, squares are only 2 triangles put together. So a cube is only 12 faces put together by 8 Vertices.
   [Cube Image](https://www.researchgate.net/publication/380174666/figure/fig3/AS:11431281251087935@1718123876571/Simple-cube-mesh-left-and-its-corresponding-OBJ-file-right.png )

(*3D Artist* will work with **Square Faces** while *Programmers* will work with **Triangles Faces**)

###### Intermediate
Each faces of the triangles now need to know where to point to because a triangle as a front (that have a face) and a back (that don't have a face). It's the job of the [[!Normals]] to define the front of a face.

To integrate textures to the object, each vertices contain a UV coordinate which define a 2D point on a texture. The texture will wrap itself to the object when rendered.
**References:**
[Wrapping Around](https://w7.pngwing.com/pngs/737/206/png-transparent-uv-mapping-texture-mapping-cube-3d-modeling-3d-computer-graphics-origami-effect-texture-angle-3d-computer-graphics.png)
[Dice Texture](https://img.favpng.com/10/18/16/uv-mapping-cube-texture-mapping-three-dimensional-space-dice-png-favpng-igXwM6pW95hRDEFPE0gC3prSk_t.jpg)
[Example on how UVs affect the texture](https://doc.babylonjs.com/img/assetPipeline/meshUVs/textureDistortion.png)

###### %Expert
With the [[!Normals]] you can find the Tangent and the Bi-Tangent:
> (?)Tangents and binormal vectors are used to determine things like torque and angular velocity, deflections of light or physical objects, and so forth. They are generally used in combination with the normal vector to give an angular 3-dimensional frame of reference to more complicated collisions, physics calculations, light deflections, and so forth; they're the additional information needed to ensure that angular momentum is preserved along the correct system of axes.
> [Source](https://gamedev.stackexchange.com/questions/51399/what-are-normal-tangent-and-binormal-vectors-and-how-are-they-used)

[[!Shaders]]

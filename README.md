# UE4-PHISMTools
### Procedural Hierarchical Instanced Static Mesh (PHISM) Tools for Unreal Engine 4.

#### [I'm currently working on a new plugin called ProInstance Tools which is a major extention based on this]

Created to simplify Level Design workflow and reduce iteration times.

PHISM Tools uses Hierarchical Instanced Static Mesh component instead of regular Static Mesh to reduce drawcalls and improve overall performance.

Some features:
* Setting up an array of meshes
* Procedural placing based on collisions
* Detecting location and angle of surface below
* Adding random location/rotation
* Randomization depends on seed number
* Optimization settings - Cull Distances, Shadows
* Clean code and shared functions

Some use cases and examples:

#### BP_PHISM_MeshesArray
![](/images/example-01.jpg)

#### BP_PHISM_MeshesRandom
![](/images/example-02.jpg)

#### BP_PHISM_SplineFences
![](/images/example-03.jpg)

#### BP_PHISM_SplineMeshes
![](/images/example-04.jpg)

#### BP_PHISM_SplineMeshesBounds
![](/images/example-05.jpg)

Current project is developed for UE4 4.19 and it basically means that you can upgrade it to any 4.19+ version of the engine.
Some parts can be WIP!

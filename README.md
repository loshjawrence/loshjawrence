# RepositoryListing
**Table of Contents**
* [Graphics Self Study](https://github.com/loshjawrence/GraphicsSelfStudy)<br />
* [Cloth Simulation](https://github.com/loshjawrence/ClothSim)<br />
* [Fluid Simulation](https://github.com/loshjawrence/FluidSim)<br />
* [Vulkan VR Simulator](https://github.com/loshjawrence/SecondaryVR)<br />
* [CUDA Path Tracer](https://github.com/loshjawrence/Project3-CUDA-Path-Tracer)<br />
* [WebGL Clustered Deferred and Clustered Forward Plus Renderer](https://github.com/loshjawrence/Project5-WebGL-Clustered-Deferred-Forward-Plus)<br />
* [Physically-Based Renderer](https://github.com/loshjawrence/Physically-Based-Rendering)<br />
* [CUDA Rasterizer](https://github.com/loshjawrence/Project4-CUDA-Rasterizer)<br />
* [Style Transfer](https://github.com/loshjawrence/AnimationStylizer)<br />
* [Mini-Minecraft](https://github.com/loshjawrence/Mini-Minecraft)<br />
* [Half-Edge Mesh Representation and Catmul-Clark Subdivision](https://github.com/loshjawrence/HalfEdgeCatmulClarkSubdivision)<br />
* [Animation Projects](https://github.com/loshjawrence/AnimationProjects)<br />
* [CUDA Boids Flocking](https://github.com/loshjawrence/Project1-CUDA-Flocking)<br />
* [CUDA Recursive Stream Compaction, Radix Sort](https://github.com/loshjawrence/Project2-Stream-Compaction)<br />


# [Graphics Self Study](https://github.com/loshjawrence/GraphicsSelfStudy)<br />
Where I learn, implement, and experiment with modern graphics techniques in OpenGL.<br />
**Cascaded Shadows,Shadow Mapping(PCF, VSM, ESM, EVSM),Horizon based SSAO, HDR, Tonemapping, Bloom, Color Grading, PBR **<br />
![](img/renderer.png)


# [Cloth Simulation](https://github.com/loshjawrence/ClothSim)<br />
Clothing simulation using Backward and Forward Euler integration.<br />
**Backward Euler (implicit)**<br />
![](img/BE.gif)

**Forward Euler (explicit).**<br />
![](img/FE.gif)

# [Fluid Simulation](https://github.com/loshjawrence/FluidSim)<br />
Fluid simulation using a Semi-Lagrangian approach with a MAC grid.<br />
![](img/conf0p5.gif)


# [Vulkan VR Simulator](https://github.com/loshjawrence/SecondaryVR)<br />
A scratch VR simulator written in vulkan. Radial density masking, Adaptive Quality, Timewarp simulation, perf comparison of several barrel distortion/chromatic aberration implementations, push constant comparison.<br />
**Timewarp Simulation. Rendering stops and warps the last frame rendered into the current view**<br />
![](img/timewarp.gif)

**Radial Density Masking mentioned in Alex Vlacho's GDC 2016 talk on VR rendering. See repo for more information.**<br />
![](img/radialdensitymask.png)


# [CUDA Path Tracer](https://github.com/loshjawrence/Project3-CUDA-Path-Tracer)<br />
A CUDA path tracer project done for CIS565 GPU Programming. It's a unidirectional path tracer with direct lighting MIS and a Jensen01 dipole model BSSRDF implementation. For work efficiency, it includes stream compaction to eliminate dead paths and material sorting to minimize thread divergence.<br />
**Diffuse vs Jensen01 bssrdf, marble**<br />
![](img/ssbunny_skin1_500.png)
![](img/ssangelmiller_skimmilk_2k.png)
![](img/glassmis5000.png)



# [WebGL Clustered Deferred and Clustered Forward Plus Renderer](https://github.com/loshjawrence/Project5-WebGL-Clustered-Deferred-Forward-Plus)<br />
A WebGL renderer that includes clustered deferred, clustered forward plus, and forward techniques for comparison. This was a project in CIS565 GPU Programming. The view frustum is broken up into a 3D cluster grid and each cluster is populated with point lights in the scene that could potentally effect the lighting in that region. This reduces the lighting computation in the fragment shader.<br />
**Clustered Deferred**<br />
![](img/clusteredDeferred.gif)
![](img/clusteredDeferred.png)



# [Physically Based Renderer](https://github.com/loshjawrence/Physically-Based-Rendering)<br />
A CPU path tracer done for CIS561 Physically Based Rendering (using Pharr, Humphreys, and Jakob's physcially based rendering book as guidance). Includes unidirectional path tracer with direct lighting MIS and a (bad)photon mapping renderer. Also includes BVH tree scene representation to reduce intersection test complexity and Kd tree to represent arbitrary meshes.<br />
**Unidirectional pathtracer with MIS, 'tangle cube' implicit surface**<br />
![](img/implicit400spp.png)

**Photon Mapping with texture mapped microfacet roughness, glass ball, plastic cube**<br />
* could use more photons to smooth out the specular spots
![](img/PM3000spp.png)



# [CUDA Rasterizer](https://github.com/loshjawrence/Project4-CUDA-Rasterizer)<br />
A software rasterizer done in CUDA for CIS565 GPU Programming. Includes perspective correct interpolation texturing and anti-aliasing.
Also did a software rasterizer (cpu) for CIS560 Intro to Computer Graphics, but this was a nice refresher.<br />
![](img/rasterblinnphong.png)
![](img/ssaacompare.png)



# [Style Transfer](https://github.com/loshjawrence/AnimationStylizer)<br />
A from-scratch SIGGRAPH paper implementation done for CIS660 Advanced Topics in Computer Graphics and Animation. This was a group project with Grace Xu. Other papers were implemented as well (Image Analogies, Patch Match) in order to implement this Pixar paper.<br />
![](img/mixfaces.png)
![](img/nosuprises.gif)



# [Mini-Minecraft](https://github.com/loshjawrence/Mini-Minecraft)<br />
A mostly from-scratch group project done for CIS560 Intro to Computer Graphics. I did terrain rendering, weather, and caves.<br />
**View of Caves From Under the Terrain**<br />
![](img/caves.gif)
![](img/snowcover.gif)


# [Half-Edge Mesh Representation and Catmul-Clark Subdivision](https://github.com/loshjawrence/HalfEdgeCatmulClarkSubdivision)<br />
A project for CIS560 exploring half-edge mesh representation for mesh manipulation and Catmul-clark subdivision.<br />
**Face Triangulation, extrusion and catmul-clark subdivision**<br />
![](img/triangulate.gif)

**Sharpness with Subdivision**<br />
![](img/sharpface.gif)



# [AnimationProjects](https://github.com/loshjawrence/AnimationProjects)<br />
Various animation projects done for CIS562 Computer Animation.<br />
![](img/IK.gif)
![](img/behaviors.gif)


# [CUDA Boids Flocking](https://github.com/loshjawrence/Project1-CUDA-Flocking)<br />
A project done for CIS565 GPU Programming implementing boids flocking.<br />
![](img/boids50k.gif)


# [Stream Compaction](https://github.com/loshjawrence/Project2-Stream-Compaction)<br />
A project done for CIS565 GPU Programming implementing exclusive scan (recursive scan for EC) and radix sort.<br />
![](img/graph_exclusivescan.png)


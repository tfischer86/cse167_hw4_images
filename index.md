# CSE 167 Final Project - Path Tracing Extra Credit

Features implemented:
- Path tracing
- A new command, `method {ray|path [samples per pixel]}`, to control which rendering method is used to draw the scene.
- Spherical lights for soft shadows
- 8x speedup for path tracing, using parallelization via openMP.

Materials can be both diffuse and specular:

![scene4 path](images/scene4-path.png)

Soft shadows occur naturally due to the use of spherical lights. Specular materials create highlights on nearby surfaces.

![scene6 path](images/scene6-path.png)

Other images:

![cornell box](images/cornell.png)


# StarTrekOpenGL with C++

This project utilizes the following model:
https://sketchfab.com/3d-models/uss-enterprise-d-star-trek-tng-e3118c97914342b3ad7dd957c4b4ce4e

The skybox was created using a cubemap in OpenGL. Here is the link for the corresponding textures for each face of the cubemap:
https://opengameart.org/content/space-skyboxes-0

The implementation within `ogl.cpp` references classes defined by the author of the online textbook at: www.learnopengl.com
(Classes used -> Mesh, Model, Shader, Camera)
A function from the Cubemaps chapter called `loadCubemap` is also referenced directly from the textbook.

# Final Rendering
![](https://github.com/dhodzic1/StarTrekOpenGL/blob/main/enterprise.gif)

This can be executed via its project.exe file.

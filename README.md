Brief Introduction:
Launch a beam of light to the scene, find the nearest intersection between the light and the geometric figure, and then calculate the color of the intersection. If the material of the intersection is reflective, it can be tracked at the intersection in the direction of reflection.

NEED: VS 2015(community), OpenGL, VC++

File Introduction:
    tracer.vcxproj, tracer.vcxproj.filters: These two projects are about Visual C++. They are used to generate project. They include so many information about platform, configuration and so on.

    main.cpp: The main file which you can run.

    gvector3.h, gvector3.cpp: These two files are about vector quantity. They can express the point(x, y, z). The files also include the operation of vector.

    cray.h, cray.cpp: These two files are about ray. We can use these files to identify if the point is on the ray.

    color.h, color.cpp: These files are used to define the color. We can use function red(), blue(), green() and Color(r, g, b). They are realized by RGB.

    csphere.h, csphere.cpp: These files define a sphere. There are two parameters: center and radius.

    perspectiveCamera.h, perspectiveCamera.cpp: The files are used for the image of the sampling position, generate a beam of light.

    plane.h, plane.cpp: These two files are used to generate a plane. The plane is under the balls.

    The other files are used to generate objects and choose materials. They are all very simple.

How To Use: 
    If you have Visual Studio, you can open the file tracer.sln directly. I suggest you use VS2015 which is totally free and convenient. After open the sln file. You can run the main.cpp successfully. If you want to test different conditions. You can modify the parameters in the function renderRecursive(). The process is too simple if you have a right environment(OpenGL). If you have compiled first, you can run /Debug/tracer.exe too.

# Homework-Exercise-1-2---27133230
Create your Own Code &amp; Create a Develop Branch

**Hi and Welcome.**

**Description**

As I was working in Unity C# I found it very annoying to create virtual worlds by hand, so I did some research and came accross Procedural Mesh. This makes use of code to generate a surface within Unity. The process makes use of triangles to build a 2D surface. This made the creation and development of virtual environments less tedious. 

**How I implemented it**

The code makes use of Vectors, each vector has 3 points(x,y,z). By changeing the "x" and "z" to a 1 we can draw the area the triangle needs to be.
We tell the system that the shape we want is a triangle by indicating it with the 3 values in the int[] array (0,1,2). From here we call the CreateShape function on Start() which will generate the triangle.

- This code will only generate one triangle at the moment but it can be combined and modified to allow it to generate an X amount of triangles that will cover a huge area.

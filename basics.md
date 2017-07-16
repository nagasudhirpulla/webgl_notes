## WorkFlow

Refer
1. https://github.com/sessamekesh/IndigoCS-webgl-tutorials/blob/master/01%20-%20Simple%20Triangle/app.js
2. https://webglfundamentals.org/webgl/lessons/webgl-fundamentals.html - 
You can even find handy functions to initialise webgl shaders, programs, uniforms, buffers, attributes, rendering etc

### Steps to draw a basic triangle
1. Get the webgl context from the html5 canvas element in the index.html page 
2. Write the vertex and fragment shaders text
3. Create the shader objects in webgl and assign shaderSources as the text we created in step 1.
Compile the shaders
4. Create a program in Webgl and attach the 2 shaders to the program. Link and validate the program
5. Create a javascript array of triangle vertices
6. Create a buffer in webgl and bind the data to the buffer
7. Get the attribute locations of the required attributes in vertex and fragment shaders from webgl as javascript objects.
Set the attribute pointer to the required buffers, so that the buffer data will be accessed when calling the attribute in the webgl shader program
8. ```enableVertexAttribArray``` for all the above attributes
9. Tell webgl to use the program by ```useProgram``` command
10. Use ```drawArrays``` command to draw the triangle arrays

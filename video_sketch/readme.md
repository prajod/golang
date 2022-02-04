__Video Sketch__

This project enables video sharing over extremely low bandwidth networks. 

That is accomplished by creating a sketch of the video frames(using edge detection), compressing the created frames of black and white pixels into byte arrays and sending that to a browser over http. Javascript code is then used in the browser to recreate the animations present in the original video.

Due to the methods used in the compression, color and shading information will be completely lost. Additionally configuartion parameters are provided to control the level of compression. These configuration parameters can be used to recover some of the shading information.

The back end is in golang, support by the gocv library for video manipulation. The front end is in javascript and svg. The React framework is used as a layer over javascript.

Notes:
This project will be iterated over continuously to
1. Add more design elements and GoF design patterns
2. Comply with SOLID principles
3. Improve componentization, configurability and reusability
4. Add more test cases
5. Reduce Technical Debt
6. Improve performance
7. Improve scalability
8. Reduce dependency on external frameworks and libraries

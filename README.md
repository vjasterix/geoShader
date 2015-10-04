# geoShader
squares
![](https://i.vimeocdn.com/video/538219175_295x166.webp)

> Licensed under Creative Commons Attribution

***

For Touchdesigner. Example of using geometry shaders. Geometry shaders are handy for taking incoming points and rending additional points / tristrips / lines at each face. There's also a displacement shader for the rear mesh looking piece. 

Video sources with fluid / smooth motion tend to work better than skitchy / jumpy / cut stuff.
Res controls the number of squares.
/Geo1 use image (button) applies the texture to the geometrys when on. Or uses the uniform picked color of the original vertex uniformly when off.

Yeah, you could do something similarish using instancing. But this is technically alot faster as all calcs are handled on the gpu.

See how I've used it at https://vimeo.com/141266387. I used a count chop attached to an incoming beat trigger to modify the resolution settings. 

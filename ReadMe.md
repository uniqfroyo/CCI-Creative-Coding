Fractal Menger Sponge caught my eyes at the first time, so I decide to choose it as my final work. A Menger Sponge is a three-dimensional fractal, which can be made by taking a cube and cutting out a square section through the center in each of the three directions; then each of the resulting smaller cubes is cut out in the same way and so on until you've removed infinitely many pieces. It’s really amazing. 

I want to start from its 2D to 3D. 2D is called Sierpiński carpet, which is a
plane fractal first described by Wacław Sierpiński in 1916. The square is cut into nine congruent subsquares in a 3-by-3 grid, and the central subsquare is removed. The same procedure is then applied recursively to the remaining eight subsquares, ad infinitum. It looks roughly the same however much zoom in or out, which is called self-similarity. And it’s what makes the fractal beautiful. Sierpiński carpet can also make some interesting animation by changing the function.

3D Menger Sponge is created based on a box. We use cross product function to make three infinite boxes, then scale the cross by one third, and perform the subtraction of the cross to the box. Do this subtraction many times, iteratively. The material is based on the iteration count, and some fake occlusion too. I translate and rotate the point p a little bit in each iteration, which can make less symmetrical patterns. I use different functions to change its forms and use the mouse to rotate it. Then, I add a plane to cut the box. Maximilian.js passed Oscwave to the shader as a uniform float, and I add mywave into the Menger Sponge fractal position to let the shape transform with the sound. I write different waves, and you can try them! I also add Ashima Simplex noise to the fractal position to explore the effects, but it seems a little strange.

![imgname](https://www.iquilezles.org/www/articles/menger/gfx05.jpg)      ![imgname](https://www.iquilezles.org/www/articles/menger/gfx05.jpg)

![imgname](https://www.iquilezles.org/www/articles/menger/gfx05.jpg)      ![imgname](https://www.iquilezles.org/www/articles/menger/gfx05.jpg)

I read many articles about fractals and learn many other fantastic fractals, like Koch snowflake, Mandelbrot Set, Julia set, Solkoch, Sierpinski triangle. "Clouds are not spheres, mountains are not cones, coastlines are not circles, and bark is not smooth, nor does lightning travel in a straight line."(Mandelbrot, 1983). Natural systems can be explained in terms of fractals, even the chromatin is a fractal and that keeps DNA from getting tangled. Fractals are complex, never-ending patterns created by repeating mathematical equations. It’s exciting to know these.

The process of learning coding from scratch is challenging. There are always lots of mathematical formulas and principles I can not understand. I often want to give up, but I know it takes a process to change from quantity to quality. What I can do is try my best to finish the works.

Links:

My Blog: https://www.froyodai.com/post/cci-s1-creative-coding-final-project

My Video: https://www.youtube.com/watch?v=EIEP90sB-iQ


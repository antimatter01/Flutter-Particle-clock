# Flutter-Particle-clock
 It randomizes the color palettes while also maintaining legibility by calculating the luminance in real-time.
Building this was a bit of a struggle as I'm not very good with math, but the framework and the developer experience (hot reload, in particular) helped me out a lot. Being able to iterate quickly is a great way to learn new things. I guess the code could be improved in several ways, both in terms of elegance and performance. However, I've managed to easily stay far below the 16ms/frame benchmark.
🎨 Randomly selects color palettes while still maintaining legibility at all times.
🌤 Supports both light mode and dark mode, by filtering background color by luminance.
📱 Scales to fit the screen space available and adjust calculations & rendering accordingly.
🚀 At least 60 FPS on modern devices.
🌈 Constantly shifting and moving, making it fun to look at.

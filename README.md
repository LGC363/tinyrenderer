# Tiny Renderer or how OpenGL works: software rendering in 500 lines of code

# Check [the wiki](https://github.com/ssloy/tinyrenderer/wiki) for the detailed lessons.

## compilation
```sh
git clone https://github.com/ssloy/tinyrenderer.git &&
cd tinyrenderer &&
mkdir build &&
cd build &&
cmake .. &&
cmake --build . -j &&
./tinyrenderer ../obj/diablo3_pose/diablo3_pose.obj ../obj/floor.obj
```
The rendered image is saved to `framebuffer.tga`.

You can open the project in Gitpod, a free online dev evironment for GitHub:
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ssloy/tinyrenderer)

On open, the editor will compile & run the program as well as open the resulting image in the editor's preview.
Just change the code in the editor and rerun the script (use the terminal's history) to see updated images.



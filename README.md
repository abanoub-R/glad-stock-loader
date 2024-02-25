# Default Glad Loader

Automatically generated from the glad2 webservice with [this](https://gen.glad.sh/#generator=c&api=gl%3D4.6&profile=gl%3Dcore%2Cgles1%3Dcommon&options=LOADER) permalink.

- I am not the creator of GLAD
- I am not associated with GLAD in any way
- This repository is strictly for ease of use and does not expand on or remove default features
- This project inherits the same license as the original [project](https://github.com/Dav1dde/glad)

## Compilation
Run the following

`clang -shared gl.c -o glad.dll`

> **_NOTE:_** The above command assumes that the include paths are left untouched
## Linkage
Run the following
`clang foo.c -lglad.dll`

> **_NOTE:_** The above command assumes that foo.c and glad.dll are in the same directory

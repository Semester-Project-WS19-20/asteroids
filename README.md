## Prerequisite
Same prerequisites as here:
https://github.com/Semester-Project-WS19-20/em-dosbox#prerequisites

## Guide to build and run asteroids

build asteroids:
`emcc asteroids/*.c -O2 -Wall -g -lm -s USE_SDL=2 -s USE_SDL_IMAGE=2 -s SDL2_IMAGE_FORMATS='["png"]' --preload-file assets --shell-file custom_shell.html -o out/asteroids.html`

run asteroids:
`emrun --no_browser --port 8080 out/asteroids.html`

## Sources
The changes to asteroids to make it work in wasm were made following this guide:
https://medium.com/@robaboukhalil/porting-games-to-the-web-with-webassembly-70d598e1a3ec

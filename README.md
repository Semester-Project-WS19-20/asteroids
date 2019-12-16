## Guide to build asteroids

`emcc -o out/asteroids.html asteroids/*.c -Wall -g -lm -s USE_SDL=2`

## Sources
The changes to asteroids to make it work in wasm were made following this guide:
https://medium.com/@robaboukhalil/porting-games-to-the-web-with-webassembly-70d598e1a3ec

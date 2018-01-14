TODO:
1. ✓ Setup emscripten toolchain (See link)
    ✓ Finish build
    ✓ Setup emcc in path

2. Setup CLion project
    - Build settings

4. Fix memory leaks / crash / segfault

5. Get audio working
    - Different buffer sizes iirc?
    - rewrite soundlib to use SDL_mixer

Possible feature list:
* Add i18n support via gettext
* make paths configurable
  * store saves/settings in user dir based on a platform
  * load data from platform-specific dir (e.g. /usr/share on linux)
  * move all custom files to data/
  * Add runtime language switching support
* drop out sif and use original data
* make compatible with nicalis version
* use wavs for drums?

NOTES:
- source emsdk/emsdk_env.sh to setup environment


Important links:
https://developer.mozilla.org/en-US/docs/WebAssembly/C_to_wasm


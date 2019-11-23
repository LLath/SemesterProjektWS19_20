# Getting DOSBox to work

* First step was to add https://github.com/dreamlayers/em-dosbox.git as subdirectory to our SemesterProjektWS19_20 Repository in the folder /InProgress/DOSBox/em-dosbox
* To be able to commit to it the git remote origin was changed to https://github.com/LLath/SemesterProjektWS19_20.git
* Following the original instructions for compiling `<./autogen.sh>` was launched
* To be able to run games the ./src/Makefile.am was changed according to https://github.com/dreamlayers/em-dosbox/issues/49
* Make sure your emscripten toolchain is available, if not run `<source ./emsdk_env.sh --build=Release>` in emsdk folder
* After saving those changes `<emconfigure ./configure --enable-wasm --disable-sync>` was started
* After theese steps build with `<make>`

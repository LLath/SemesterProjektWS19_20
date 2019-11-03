# SemesterProjektWS19_20

## Guide to start rouge.js

Follow steps on https://webassembly.org/getting-started/developers-guide/

Clone rogue repository:  
`git clone https://github.com/mad4j/rogue.js rogue`

change directory to dist:  
`cd rogue/dist/`

start emrun webserver:  
`emrun --no_browser --port 8080 roguejs.1.0.0-XX.html` // replace XX with actual version number

open http://localhost:8080/ in your browser  

## Guide to build asteroids

in asteroids folder:
`emcc -o app.html asteroids/*.c -Wall -g -lm -s USE_SDL=2`

## Guide on submodules:

https://git-scm.com/book/en/v2/Git-Tools-Submodules

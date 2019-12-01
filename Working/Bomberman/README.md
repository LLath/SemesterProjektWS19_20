## How to get bomberman running
1. Need to install rustup  
`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`  

2. `source $HOME/.cargo/env`  
So your current terminal has access to $PATH

3. `curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh`  
Install wasm-pack

Next steps are also in the original README  
4. `npm i`  
5. `npm run build`  
6. `npm run serve`

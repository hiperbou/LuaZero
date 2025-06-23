# LuaZero
Customized Lua 5.1

Includes patches like zero evaluated to false, and emscripten makefile.



git clone https://github.com/emscripten-core/emsdk.git
cd emsdk
./emsdk update
git pull
./emsdk install latest
./emsdk activate latest
source ./emsdk_env.sh
emcc --version

cd src
make generic
make generic
cp liblua.a lua luac lua.wasm ../out/
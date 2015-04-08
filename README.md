# LuaWindowsBuildScript
Build latest Lua for Windows In Visual Studio


**For Development**

# Lua 5.3 (c-style static library)

First use your favourite environment get the source tree and put the **CMakeLists.txt** into same directory with **src** and **doc** etc. You can use WinRAR or 7-zip.

```bash
git clone https://github.com/rexdf/LuaWindowsBuildScript.git
git checkout dev
wget http://www.lua.org/ftp/lua-5.3.0.tar.gz
tar zxvf lua-5.3.0.tar.gz
mv lua-5.3.0/* LuaWindowsBuildScript/
```

Now Open cmd.exe with [cmake](http://www.cmake.org).exe in path, typical you can type `path=C:\Program Files (x86)\CMake\bin;%path%` in the cmd. And now cmd goto the **LuaWindowsBuildScript** directory. Use VS 2013 as following.

	cmake  -G "Visual Studio 12"

You can use `cmake --help` to get detail about build command.

Now open **lua.sln** with VS 2013 and build it.


[luarocks](http://luarocks.org) maybe need this one.

[LuaFilesystem](https://rocks.moonscript.org/modules/hisham/luafilesystem)

![luarocks](https://raw.githubusercontent.com/rexdf/LuaWindowsBuildScript/master/screenshot/luabuild.png)
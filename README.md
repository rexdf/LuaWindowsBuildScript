# LuaWindowsBuildScript
Build latest Lua for Windows In Visual Studio


**For Development**

# Lua 5.3

	git clone https://github.com/rexdf/LuaWindowsBuildScript.git
	git checkout dev

Now Open cmd.exe with cmake.exe in path, typical you can type `path=C:\Program Files (x86)\CMake\bin;%path%` in the cmd. And now goto the **LuaWindowsBuildScript** directory.

	cmake  -G "Visual Studio 12"

You can use `cmake --help` to get detail about build command.

Now open **lua.sln** with VS 2013 and build it.


بسم الله الرحمن الرحيم
la ilaha illa Allah Mohammed Rassoul Allah

# popping dikr
BismiAllah, a Dikhr app that shows itself every now and then

# BUILDING
1. install `zig 0.12`
2. run `zig build`
if you are on linux you need to install `SDL2` and `SDL2_ttf`

### Win64 BUILD:
* from `x64 Native Tools Command Prompt for VS`
* [Install & Integrate VCPKG](https://learn.microsoft.com/en-us/vcpkg/examples/installing-and-using-packages)
* Install dependencies through VCPKG.
* `scripts\build.bat -b` to build `.sln` & `compile_commands.json`. (check DCMAKE_TOOLCHAIN_FILE path)
* `scripts\build.bat -cr` to compile & run exe.


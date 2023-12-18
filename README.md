# vcpkg-opengl

go to c:\ folder
create new folder and put name "src" 
go inside src folder
right click then open src folder in gitbash
type command : git clone https://github.com/Microsoft/vcpkg.git
then type: cd vcpkg
then type: .\vcpkg\bootstrap-vcpkg.bat

then open terminal or powershell
then type: cd src
then type: cd vcpkg   
then type: .\vcpkg integrate install
then type: .\vcpkg install freeglut:x64-windows
then type: .\vcpkg install glew
then type: .\vcpkg install glfw3


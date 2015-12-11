# pumpkin
Golang lroc/cef example: the Embeddable HTML 5 engine for modern UI development

How to build on Windows platform (Win7 32/64-bit).
-------------------

1. Make sure you have installed windows-386 version of Go (for example: 1.5.1)
2. Install mingw and add C:\MinGW\bin to PATH. You can install mingw using mingw-get-setup.exe. Select packages to install: "mingw-developer-toolkit", "mingw32-base", "msys-base".
3. Download CEF 3 branch 2171 revision 1897 binaries: 
   [cef_binary_3.2171.1897_windows32.7z](https://github.com/lroc/cef/releases/download/cef_3.2171.1897/cef_binary_3.2171.1897_windows32.7z)
   Copy Release/* to cef/Release
   Copy Resources/* to cef/Release
4. Run "build.bat" in the directory

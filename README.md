# Hello World Example - Visual Studio 2022

https://docs.wxwidgets.org/latest/overview_helloworld.html

![Sem título](https://user-images.githubusercontent.com/98597119/217324665-1966ebce-0778-402e-b651-6df119d71ecb.png)

This page shows a very simple wxWidgets program that can be used as a skeleton for your own code.

While it does nothing very useful, it introduces a couple of important concepts and explains how to write a working wxWidgets application. Trying building and running this application is also a good way of checking that wxWidgets is correctly installed on your system. And if you haven't installed wxWidgets yet, please do it first.

## Downloads Latest Stable Release: 3.2.1

https://www.wxwidgets.org/downloads/

https://github.com/wxWidgets/wxWidgets/releases/download/v3.2.1/wxWidgets-3.2.1.zip

## Installing wxWidgets for Windows

https://docs.wxwidgets.org/trunk/plat_msw_install.html

This is wxWidgets for Microsoft Windows 7 or later (up to 11) including both 32 bit and 64 bit versions.

## Adding an Environment Variable under Windows

https://wiki.wxwidgets.org/Adding_an_Environment_Variable_under_Windows

![Sem título-24](https://user-images.githubusercontent.com/98597119/217841175-3bc721f4-5a8f-4504-a49a-4bb409d6789e.png)

## Building wxWidgets

The following sections explain how to compile wxWidgets with each supported compiler, see the "Building Applications" section about the instructions for building your application using wxWidgets.

All makefiles and project are located in build\msw directory.

Ready to use project files are provided for VC++ versions 2015, 2017, 2019 and 2022.

Simply open wx_vcN.sln (for N=14, 15, 16 or 17) file, select the appropriate configuration (Debug or Release, static or DLL) and build the solution. Notice that when building a DLL configuration, you may need to perform the build several times because the projects are not always built in the correct order, and this may result in link errors. Simply do the build again, up to 3 times, to fix this.

From the Menu IDE

Eg: 

File -> Open -> Folder

C:\wxWidgets-3.2.1\build\msw\wx_vc17.sln

![QgBwu-878412810](https://user-images.githubusercontent.com/98597119/217882191-12b55c96-b06a-4d2c-a0d6-971e82fef4c6.jpg)

## Microsoft Visual C++ Compilation

From the Menu IDE

Eg:

Build -> Build Solution

![visual-studio-build-solution-1646433852](https://user-images.githubusercontent.com/98597119/217879919-856c90b9-2d35-46f7-9039-c55ece857042.jpg)

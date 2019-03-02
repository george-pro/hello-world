[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source-175x29.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit-150x33.png?v=103)](https://opensource.org/licenses/mit-license.php)

This project is meant to help others run through the basic steps of getting a basic "Hello, world!" program up and running. 


# Hello, Command Line!

  Start by opening cmd.exe from inside the hello-world folder.
  '>>' means run from the command line

## C
Install:
  [MinGW Installation Manager (mingw-get)](https://osdn.net/projects/mingw/releases/)
Create:
  Create a '.c' file to contain your C source code (see included source code for an example)
Compile:
  >> gcc HelloC.c -o HelloC
  Creates an '.exe' file
Run:
  >> HelloC

## C\#
Install:
  [.Net Core 2.2](https://dotnet.microsoft.com/download)
Create:
  >> dotnet new console -o HelloC#
  Creates folder w/ files ending in '.cs' & '.csproj' extensions
  '.cs' is the C# source code
  '.csproj' is the C# project settings/references file
Edit:
  Edit the '.cs' file as you see fit
Run:
  >> cd HelloC#
  >> dotnet run

## C++
Install:
  [MinGW Installation Manager (mingw-get)](https://osdn.net/projects/mingw/releases/)
  Same download as C (see above)
Create:
  Create a '.cpp' file to contain your C++ source code (see included source code for an example)
Compile:
  >> g++ HelloC++.cpp -o HelloC++
  Creates an '.exe' file
Run:
  >> HelloC++

## HTML/CSS/JavaScript
Create:
  Create an '.html' file to contain your HTML code (see included source code for an example)
  Create a '.css' file to contain your CSS code (see included source code for an example)
  Create a '.js' file to contain your JavaScript code (see included source code for an example)
  Be sure to add a link to your '.css' and '.js' files in your '.html' file!
Run:
  >> HelloHTML.html

## Java
Install:
  [Java Development Kit (JDK)](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
Create:
  Create a '.java' file to contain your Java source code (see included source code for an example)
Compile:
  >> javac HelloJava.java
  Creates a '.class' file
Run:
  >> java HelloJava

## Python 2
Install:
  [Windows x86-64 MSI Installer for Python 2](https://www.python.org/downloads/release/python-2715/)
Create:
  Create a '.py' file to contain your Python 2 code (see included source code for an example)
Run:
  >> python HelloPython2.py

## Python 3
Install:
  [Windows x86-64 executable installer for Python 3](https://www.python.org/downloads/release/python-372/)
Create:
  Create a '.py' file to contain your Python 3 code (see included source code for an example)
Run:
  >> python HelloPython3.py

﻿# ROT13 APP
</br>

### Table of Contents

 1. [About Project](https://github.com/Code-Blender-7/Mini_Apps/blob/main/ROT13%20App/Readme.md#about-project)
 2. [Project Overview and Demo](https://github.com/Code-Blender-7/Mini_Apps/tree/main/ROT13%20App#project-overview-and-demo)
 3. [PyQt5 Introduction](https://github.com/Code-Blender-7/Mini_Apps/tree/main/ROT13%20App#pyqt5-introduction)
 4. [How to run it?](https://github.com/Code-Blender-7/Mini_Apps/tree/main/ROT13%20App#how-to-install)
 5. [Future Addins](https://github.com/Code-Blender-7/Mini_Apps/tree/main/ROT13%20App#future-addins)
 6. [Updates](https://github.com/Code-Blender-7/Mini_Apps/tree/main/ROT13%20App#updates--)
 
### About Project
The ROT13 app is a GUI implementation of the original ROT13 encryption. This program is created by using the PyQT5 module on python with CSS styling! 

I created this program because I got bored with the terminal and decided to host my programs with an "app" kind of a interface. That is why I created this program. The designs and app interface is done by me while the encryption algorithm is done by Sam Allen. </br>
You can find the encryption code [here](https://www.dotnetperls.com/rot13-python) :)

//////////////////////////////////////////////////////////////////////////////

### Project Overview and Demo
This is the project overview using the default theme.
![image 1](https://github.com/Code-Blender-7/assets/blob/main/Mini-Apps/ROT13%20App/1.png)

You can find the Demo via this [twitter link!](https://twitter.com/Black_2_white/status/1381659824409079808)


//////////////////////////////////////////////////////////////////////////////


### PyQT5 Introduction
The infamous PyQt5 is a python module that is used for Graphical User Interface[GUI] development. PyQt5 is packed with amazing basic yet interesting widgets which can be almost customizable in any form that you like! \
PyQt5 originally comes from the Qt v5 (*PyPI from 2021*)  which is framework that is generally focused on C++. For starters, the PyQt5 is still not perfect as that PyQt5 is no ordinary module with small tutorials and studies to master it. It requires a lot of learning and practice to master it. The PyQt5 Documentations are also not fully complete yet and the original wiki is focused on the C++. \
The Qt5 Framework do support Python language. It is thus recommended that you get along the basic stuff and move on to the interesting hardcore development.
</br>
Beside the raw coding, it is vital that you learn about these two software for creating applications of insane creativity! 

 1. [Qt Designer](https://www.qt.io/design)
 2. [Qt Creator](https://www.qt.io/product/development-tools) </br>


//////////////////////////////////////////////////////////////////////////////


Installation of pyqt5 module
```
pip install pyqt5
```


### How to install?

<h4>
    
 You can clone the repo for the code using git. 
</h4>

```
git clone https://github.com/Code-Blender-7/Mini_Apps
```

or download the files of this project in zip by using Downgit [here](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/Code-Blender-7/Mini_Apps/tree/main/ROT13%20App).


_code ran on python version 3.9.1 on Win10_

You can also download the file and then run the script setup file to build the app yourself should you wish. *Note that it works for Windows only for now..*

```diff
-Please note that the builtin .exe may not run until you installed the following libraries.
+ $ pip install PyQt5
+ $ pip install pyperclip
+ $ pip install cx_Freeze
```
After you installed the libraries, add this to your command line to build the program internally.
```
$ python setup-build-script.py build
```
I'll find a way to make it  be available for MacOS too.

</br>


//////////////////////////////////////////////////////////////////////////////


<h4>Details of the files</h4>

[app.py](https://github.com/Code-Blender-7/Mini_Apps/blob/main/ROT13%20App/Program-Files/app.py)- Main python script inheriting the source code.

[design.css](https://github.com/Code-Blender-7/Mini_Apps/blob/main/ROT13%20App/Program-Files/design.css)- Main css script for the widget personalizations. 

[resoures.py](https://github.com/Code-Blender-7/Mini_Apps/blob/main/ROT13%20App/Program-Files/resources.py)- Computer generated .qt resource file  data for the additional icons and images the <b>app.py</b> is using for its appearance. 
</p>


//////////////////////////////////////////////////////////////////////////////


<b>⚠WARNING!⚠ </b> </br>

Without the **resource.py**, the program would trackback an error. Basically the icons are converted from a .png file into a .qml data by using the [Qt resource system.](https://doc.qt.io/qt-5/resources.html) </br>
You can learn how to design your GUI apps with using the Qt resource collection file with an example [here](https://realpython.com/python-menus-toolbars/). </br>


//////////////////////////////////////////////////////////////////////////////


### Future Addins
These are future addins that you can expect in the future!

✅ Change the theme to nebula theme.
</br>
❌ Add a execuetable file for installing.
</br>
✅ Added new built-in executable script file
 
//////////////////////////////////////////////////////////////////////////////

 
### Updates -
1. The Original theme has been replaced with the ___nebula___ theme.
2. Unnecessary lines of code has been removed from app.py
3. Rot13 Program changed into ROT13 GUI. 
4. .EXE file removed.
5. Working on creating a script based exe builder.


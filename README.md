# Minimalistic Flat Modern GUI Template
[![GitHub](https://img.shields.io/github/license/anjalp/Minimalistic-Flat-Modern-GUI-Template?logo=Github)](https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/LICENSE) [![GitHub top language](https://img.shields.io/github/languages/top/anjalp/Minimalistic-Flat-Modern-GUI-Template?logo=github)](https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template) [![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/anjalp/Minimalistic-Flat-Modern-GUI-Template?logo=github)](https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template) [![GitHub issues](https://img.shields.io/github/issues/anjalp/Minimalistic-Flat-Modern-GUI-Template?logo=github)](https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/issues)

A **Free** to use, Beautiful, Feature Rich, Fully Customizable Flat Modern GUI Template Using **Pyside2** designed in **Qt Designer**, supported for Windows/Linux/Mac OS, Incorporating widgets like Buttons, Progress Bar, Custom Tabs, and many more.

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/homepage.png">
</p>

Check below to see more Images of the GUI.

## HIGHLIGHTS

* Flat Minimalistic Design.
* Dual Tone Color Scheme.
* Dedicated Menu Bar.
* Dedicated About Page.
* Toggle Menu Button.
* Custom Top Bar With Custom Minimize, Maximize, Restore, and Close Buttons.
* Custom Widgets:
  * Push Buttons
  * Progress Bar
  * Radio Buttons
  * Check Boxes
  * Text Edit Field
  * Horizontal and Vertical Sliders
  * Horizontal and Vertical Scroll Bar
  * Combo Box.
  * Text Browser
* Custom Dialog Box with customizable Heading, Message to Display, Buttons to Display.
* Custom Error Box with customizable Heading, Message to Display, and Button.



## PREREQUISITES

* Intermediate Python User

* Comfortable in coding Pyside2/PyQt5/PyQt4 or has been using any other Python GUI package(refer to Resource section).

* Install [PySide2](https://pypi.org/project/PySide2/), [Qt Designer](https://build-system.fman.io/qt-designer-download)

* Comfortable in using Qt Designer.

  If you are completely new to GUI in python, then I suggest you quickly head forward to the Resource section for help.

## QUICKSTART

Clone/Fork the Repository to your PC, open the `/exe` folder and run the `main.exe` file to experience the GUI in a glance(don't forget that `icons` folder is required for main.exe to work.).

* If you have installed the PySide2, then try running the `main.py` 

  ```basic
  C:/User/home/minimalistic-flat-modern-ui>python3 main.py
  ```

  from your favorite terminal. 

* To modify the Main Window Design open the `ui_main.py` file in **Qt Designer**, make necessary modifications, and then the action of the widget can be coded in the `main.py` and `ui_function.py` files.

* To Modify the Dialog Box Design open the `ui_dialog.ui` file in Qt Designer, for coding related to Dialog Box, move to `class` `dialogUi` in `main.py`.The Same applies to the Error Box.

* All the Custom Stylesheet used in this Project is provided in the `Documentation.pdf` file. Use them where ever required.

* Check the `images` folder to see the GUI Images.

## LAYOUT

The Layout of the GUI is made using Qt Designer, gives you easy access to the *widget name* used in this project so that you can modify the GUI to fit your purpose with ease.

*This below illustration only represents the superficial part of the GUI. Widget inside the Stacked pages listed in the image, is not displayed here. The full representation is given in the `Documentation.pdf` file.*



![Layout](https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/layoutAsset%2097.png)

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/layout_infoAsset%20100.png">
</p>

## DOCUMENTATION

For Complete Documentation check the `Documentation.pdf`. Each python file is commented well for your reference.The Stylesheet used in this project is also provided in the pdf itself.

## QUICK GLANCE

**Color Scheme**

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/color%20scheme.png">
</p>

**Fonts**

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/font%20schem.png">
</p>

**Home Page**

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/homeDetailed.png">
</p>

**Toggle About** 

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/about%20pageAsset%2096.png">
</p>

**Page Within a Page**

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/android.png">
</p>

**Dialog Box and Error Box**

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/dialogerro.png">
</p>

**Widgets** 

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/buttons.png">
</p>

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/widget%202.png">
</p>

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/widget3.png">
</p>

**Stock Size and Full Screen**

*Stock Size*

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/about_home.PNG">
</p>

*Full Screen*

<p align="center">
  <img src="https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template/blob/master/images/about_full%20screen.PNG">
</p>

## RESOURCES

* Python Library used: [Pyside2](https://pypi.org/project/PySide2/)

* Qt Designer : [Download](https://build-system.fman.io/qt-designer-download)

* Python Basic Pyside2 Programming:
  * [Parwiz Forogh](https://www.youtube.com/watch?v=oQTxJrDRCxg&list=PL1FgJUcJJ03tiCC6a7sF8NKLBPY4jRjmS) PySide2 GUI Tutorial in his YouTube Channel: **One of the Best for Beginners**.
  * GeekForGeek: best Guides for PySide2/PyQt5.

  * Tutorial Point [PyQt Tutorials](https://www.tutorialspoint.com/pyqt/index.htm): Even though they are for the PyQt4, almost work with PySide2. 
* Pyside2 Stylesheet Documentation: [Qt For Python](https://doc.qt.io/qtforpython/overviews/stylesheet-examples.html)

## SUPPORT

:smiley: Support my work by forking or downloading this project, check it out, and share the experience.

:smiley: Support like this motivates me to do more creative, work for Open Source.

:point_right: Check out my other Projects in the [My GitHub Profile](https://github.com/anjalp)

* Hiding Files inside an Image: Project Image Steganography
* Backup your PC and Android wirelessly using the Ultra Backup Software.

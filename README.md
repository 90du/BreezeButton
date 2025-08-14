# BreezeButton

## Overview
BreezeButtonis a fork of BreezeEnhanced with the following changes:

 * Redesigned macOS like button

BreezeEnhanced is a fork of KDE Breeze decoration with the following changes:

 * The optional title-bar gradient is smooth and has a configurable intensity.
 * The title-bar opacity is configurable.
 * A very mild light line is added to the top of title-bar (especially for dark color schemes) and the separator between title-bar and window is removed.
 * By default, the close, minimize and maximize buttons are macOS-like and their sizes change on mouse-over when animation is enabled.
 * The spacing between buttons is configurable.
 * Opaqueness, opacity override and flatness are added to the exception list properties.
 * The title-bar font is set independently of the KDE font settings (for use outside KDE).

Breeze is very beautiful by default, you just need to change the color you like

## Credits:

BreezeEnhanced was started from [BreezeBlurred](https://github.com/alex47/BreezeBlurred), a former fork of Breeze with title-bar translucency and blurring.

Needless to say, the main work behind BreezeEnhanced is the Breeze KWin decoration itself, which can be downloaded from <https://download.kde.org/stable/plasma/>.

## Installation

The version number in the file [NEWS](NEWS) shows the main version of KWin that is required for the compilation. *Compilation should not be done against other versions of KWin!*

In what follows, it is supposed that the name of the installation directory of KDE libraries is `lib` and the installation prefix is `/usr`. If they are different in your distro, please replace them!

Open a terminal inside the source directory and do:
```sh
mkdir build && cd build
cmake .. -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_BUILD_TYPE=Release -DKDE_INSTALL_LIBDIR=lib -DBUILD_TESTING=OFF -DKDE_INSTALL_USE_QT_SYS_PATHS=ON
make
sudo make install
```
After the installation, restart KWin by logging out and in. Then, BreezeEnhanced will appear in *System Settings &rarr; Application Style &rarr; Window Decorations*.


## ScreenShot
<img width="858" height="1002" alt="light" src="https://github.com/user-attachments/assets/d5f51d63-ef7b-4b99-b481-96864f374de5" />


<img width="858" height="1002" alt="dark" src="https://github.com/user-attachments/assets/e7e238d2-331c-4e2b-b2be-585fcf653c88" />


[button.webm](https://github.com/user-attachments/assets/484131a7-6521-4f39-9a40-dc8bca3835d3)



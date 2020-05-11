# Pyduino 

### Arduino Control using Python.

![shot](https://user-images.githubusercontent.com/64916997/81485452-973e8d80-9266-11ea-83c8-7fb436ab90b9.png)

## User manual:
* Build it yourself:
  * [Download or clone repository](#setup)
  * [Install the modules](#modules)
  * [Connect and use](#build)
* [Download binaries](https://github.com/Muhammadrasul446/Pyduino/raw/master/Build/ArduinoControl)
### Setup

#### Go to a directory, in which you'd like to save it:
> `cd ~/Dir/Dir/dir`

#### Then clone the repository:
> `git clone https://github.com/Muhammadrasul446/Pyduino.git`

#### Or download .zip archive:
![zip](https://user-images.githubusercontent.com/64916997/81459886-62293100-91bb-11ea-8c42-8f355dc8c021.png)

### Modules

This program requires only two modules - [PySimpleGUI](https://pypi.org/project/PySimpleGUI/) and [pyFirmata](https://pypi.org/project/pyFirmata/). You can install them straightly from terminal:

> `python* -m pip install PySimpleGUI`

and:

> `python* -m pip install pyFirmata`

Where `*` is your python version.

[PySimpleGUI](https://pypi.org/project/PySimpleGUI/) requires another module, named [tkinter](https://wiki.python.org/moin/TkInter), it comes with python package, but it might be missing. In Windows you just install it like a python-module from the command line:

> `python* -m pip install tkinter`

In Unix-like Systems u can install it like a package, using your package manager:

> `sudo apt-get install python*-tk`

Where `*` is your python version.

### Build


For building binaries you'll need one more python module named [pyinstaller](https://pypi.org/project/PyInstaller/).
You can just install it from terminal:

> `python* -m install pyinstaller`

Where `*` is your python version.

Go to the directory where you saved the files, and type:

> `pyinstaller Pyduino.py --onefile`

This will give several folders in your directory. The binary is in `dist` folder. Open it and run the program!

#### Board config

Before combining a program with your board, you need to upload a `StandardFirmata` sketch to your board. It comes with arduino example-sketches:

![StandardFirmata](https://user-images.githubusercontent.com/64916997/81460364-60ad3800-91be-11ea-9ca0-b596d00c166e.png)


### My Contacts

**[Twitter](https://twitter.com/A_M_R_4_4_6)**
**[Stackoverflow](https://stackoverflow.com/users/13490404/muhammadrasul)**
**[Linkedin](https://www.linkedin.com/in/muhammadrasul-abdulhayev-6644821a9/)**
**[Sololearn](https://www.sololearn.com/Profile/13162535)**
**[Telegram](https://t.me/A_M_R_4_4_6)**

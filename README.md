[![st logo](st.png)](https://st.suckless.org/)
# Koziej's custom build of st - the simple (suckless) terminal
> *rtfm* doesn't really apply here... the source code is the documentation!

![Example of st running on my system](sample.png)

## Overview
st is considered by many the best terminal emulator available.
It is actively developed and maintained by the [suckless](https://suckless.org/) development team.
The main motivation behind st was to create a terminal emulator that is not bloated.
The suckless developers follow a strict philosophy of maintaining software that focuses on simplicity and clarity which often means features that most come to expect from a terminal emulator are not included.
As a result, if users would like extended functionality they must **manually** patch the source code and compile the program, which leads to the motivation behind my fork of st.

## Extra Features
* Transparency *(disabled for the current color scheme)*
* [Nord](https://www.nordtheme.com/) Theme
* Hidden Cursor when keyboard input is detected
* Dynamic internal padding so characters have even gaps when the window is resized

### Applied Patches
| Patch | Version |
| :-- | --: |
| [alpha](https://st.suckless.org/patches/alpha/) | [0.8.2](https://st.suckless.org/patches/alpha/st-alpha-0.8.2.diff) | 
| [anysize](https://st.suckless.org/patches/anysize/) | [0.8.1](https://st.suckless.org/patches/anysize/st-anysize-0.8.1.diff) |
| [hidecursor](https://st.suckless.org/patches/hidecursor/) | [0.8.1](https://st.suckless.org/patches/hidecursor/st-hidecursor-0.8.1.diff) |
| [no bold colors](https://st.suckless.org/patches/solarized/) | [20170623-b331da5](https://st.suckless.org/patches/solarized/st-no_bold_colors-20170623-b331da5.diff) |

## Installation & Use
To install st clone the repository and run `make`.
```sh
git clone https://github.com/jacobkoziej/st.git
cd st
sudo make install
```
To start st execute `st`.

For detailed information regarding st read the man page by running `man st` or visit [st's website](https://st.suckless.org).

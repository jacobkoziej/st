[![st logo](st.png)](https://st.suckless.org/)
# Koziej's custom build of st - the simple (suckless) terminal
> *rtfm* doesn't really apply here... the source code is the documentation!

## Unique Features
* Transparency *(disabled for current color scheme)*
* [Nord](https://www.nordtheme.com/) Theme
* Hidden Cursor when keyboard input is detected
* Dynamic internal padding so characters have even gaps when the window is resized

## Installation
```bash
git clone https://github.com/jacobkoziej/st.git
cd st
sudo make install
```

## Applied Patches
| Patch | Version |
| :-- | --: |
| [alpha](https://st.suckless.org/patches/alpha/) | [0.8.2](https://st.suckless.org/patches/alpha/st-alpha-0.8.2.diff) | 
| [anysize](https://st.suckless.org/patches/anysize/) | [0.8.1](https://st.suckless.org/patches/anysize/st-anysize-0.8.1.diff) |
| [hidecursor](https://st.suckless.org/patches/hidecursor/) | [0.8.1](https://st.suckless.org/patches/hidecursor/st-hidecursor-0.8.1.diff) |
| [no bold colors](https://st.suckless.org/patches/solarized/) | [20170623-b331da5](https://st.suckless.org/patches/solarized/st-no_bold_colors-20170623-b331da5.diff) |

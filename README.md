
<h1 align="center">
  <img src="https://github.com/Hudson-Liu/Nordic-Tabbed/blob/master/suckless_logo.png" width="30%">
  <br>
  Nordic-Themed Tabs for BSPWM
  <br>
  <img src="https://img.shields.io/github/commit-activity/y/Hudson-Liu/Nordic-Tabbed?style=for-the-badge&labelColor=%234c566a&color=%235e81ac" alt="Commit Frequency">
  <img src="https://img.shields.io/github/license/Hudson-Liu/Nordic-Tabbed?style=for-the-badge&labelColor=%234c566a&color=%235e81ac" alt="License">
</h1>

A merged fork of both [Tabbed Flexipatch](https://github.com/bakkeby/tabbed-flexipatch) and [Bsptab](https://github.com/albertored11/bsptab), customized with the Nord theme (and other minor style adjustments). This repo is essentially a preconfigured setup for `tabbed` on BSPWM.

## Installation
### Step 0: Dependencies
For Bsptab, make sure that all of the dependencies are installed. Missing any packages (e.g. `xdotool`) will cause the program to not work (blank windows may be created upon running the commands).
- `awk`
- `xwininfo`
- `xprop`
- `xdotools`
### Step 1: Install 
To install `tabbed-flexipatch`, run the following commands from within the "Nordic-Tabbed" directory (the directory level of this README.md):
```bash
cd "Tabbed Flexipatch"
sudo make clean install
cd ..
```
Then, to install Bsptab:
```bash
sudo make install
cd ..
```
### Step 2: Change Configs
If you'd like, you can change any of the configurations via the `config.h` header files. Re-run **Step 1** to apply changes.

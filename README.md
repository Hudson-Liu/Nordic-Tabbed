
Nordic-Themed Tabs for BSPWM
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

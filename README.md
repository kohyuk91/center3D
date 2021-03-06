# Center3D

## What does it do
Center the selected transform(s) onto the camera view in Maya. Just like in 3DEqualizer.

> ![img/center3d_compare_120f.gif](img/center3d_compare_120f.gif)<br>
> Image Courtesy of Hollywood Camera Work

## Video Overview
> [![](http://img.youtube.com/vi/ODW9kjdt-As/0.jpg)](http://www.youtube.com/watch?v=ODW9kjdt-As "") <br>
> [Center3D - Youtube](https://youtu.be/ODW9kjdt-As)


## Installation

### 1. Copy `center3d.py` to:
- Windows
    > \Users\USERNAME\Documents\maya\MAYAVERSION\prefs\scripts
- Mac
    > $HOME/Library/Preferences/Autodesk/maya/MAYAVERSION/prefs/scripts
- Linux
    > $HOME/maya/MAYAVERSION/prefs/scripts

### 2. Set Hotkey
1. Open **Hotkey Editor** (Windows > Settings/Preferences > Hotkey Editor)
1. Create a new 'Runtime Command'
    > ![img/hotkey_editor_new_runtime_command.png](img/hotkey_editor_new_runtime_command.png) <br>
    1. Edit Hotkeys For: Custom Scripts
    1. Runtime Command Editor
    1. New
    1. ```
       Name: center3d
       Description: center3d
       Language: Python
       ```
    1. ```
       import center3d
       center3d.main()
       ```
    1. Save Runtime Command
1. Set Hotkey
    > ![img/hotkey_editor_set_hotkey.png](img/hotkey_editor_set_hotkey.png) <br>
    1. Double click Hotkey cell
    1. Assign Hotkey
        - e.g. `Alt + Shift + C`
    1. Save and Close

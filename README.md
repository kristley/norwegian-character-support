# Norwegian character support
This program gives you Norwegian characters on (US) International keyboard layout when holding down CTRL

The program is built with Auto Hotkey, and can be edited through the .ahk-file in this repo. 

This repo includes the executable version of the program as well, so no compilation will be necessary.

## About the code

In the .ahk-file there is a binding using ctrl for the lower-case letters, and a binding using both ctrl and shift for the capital letters. Normally this wouldn't be necessary, but it seems to be necessary for foreign letters.

For more information about the .ahk scripting language, check out the [documentation](https://www.autohotkey.com/docs/AutoHotkey.htm)

## How to edit the program

If you want to edit the program you have to edit the .ahk-file. To run the .ahk-file you have to download [AutoHotkey](https://www.autohotkey.com/) and either run it through AutoHotkey, or convert it to an executable (.exe) by using "Convert .ahk to .exe" that comes with the AutoHotkey program.

## How to make the script run on startup

Windows: 

1. Download this this repo as a .zip folder. 
2. Open the "Startup" folder in Windows by pressing Windows-key + R, and typing in `shell:startup`
3. Extract the `NorwayLanguage.exe` file to the "Startup" folder

And that should be it!

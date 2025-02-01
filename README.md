# Helper
**A lightweight utility that will speed up your work.**

## **Features**
**Translate selected and copied text and instantly write it in the same place.**
_"Select a text in any program (e.g. “Bugün dışarıda yürüyüş yapmayı planlıyorum çünkü hava çok güzel.”), copy it, do not leave the selected area, press the default CTRL+ALT+C keys and when the translation is complete, the translated version will be quickly typed in the selected area with a voice. (Result "I plan to walk outside today because the weather is very nice.")"_

**Solve a selected and copied math operation and instantly write the answer in the same place.**
_"Select a text in any program (e.g. “25+5*(5-33/1.3)”) copy it, do not leave the selected area, press the default CTRL+SHIFT keys, the result will be quickly written in the selected area with a sound when the operation is completed. (Result “-76.92307692307692”)"_

**Quickly average out of windows/side windows.**
_"Press CTRL+ALT+X on a focused window and the focused window will be placed in the center of the screen."_

**Quickly search for selected text in search engines of your choice.**
_"Select a text in any program, press the default ALT+1/ALT+2 keys and search for the selected text in the default browser ("ALT+1 Search Engine 1" "ALT+2 Search Engine 2", "Default Search Engine 1 DuckDuckGo" "Default Search Engine 2 Google")"_
##
**If you are going to customize, you can download and edit the source code, then package it with pyinstaller and use it as exe, if you are not going to customize, you can download it from the release section to use the defaults.**
## Package (exe)
```
pyinstaller --onefile --noconsole --add-data "assets/helper.ico;assets" --add-data "assets/helper.png;assets" --add-data "assets/sounds/completed.mp3;assets/sounds" --add-data "assets/sounds/error.mp3;assets/sounds" --icon=assets/helper.ico helper.py
```

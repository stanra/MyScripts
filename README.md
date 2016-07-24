# MyScripts
Collection of more or less useful scripts


# Letting the scripts be used

## Shebang line :
Needed to run the scripts from command prompt!

From *automate the boring stuff with python* :
> * On Windows, the shebang line is #! python3.
> * On OS X, the shebang line is #! /usr/bin/env python3.
> * On Linux, the shebang line is #! /usr/bin/python3.

This is not a good way to do it. The shebang line is not useful in Windows, and the one should be used for Linux systems is `#! /usr/bin/env python3`. It will simply be counted as a comment on windows so it is the most portable solution.

## Run the scripts easily

On Windows :
Create a `MyScripts` folder (or any name) and add it to the path in the environment variables. In this folder, for each script, create a `.bat` file with the name of the script and the command `python <path\to\the\script.py'>`.
 Now you can simply run them from the command promt! 
 
 Could go even further by assigning a hotkey to run the script :
 simply create a shortcut of the `*.bat`, go to its properties and assign it a ! (should be in the desktop or Start Menu ? ).
 (if needed, take a look at `autohotkey`)
 
 Calling a file .pyw makes it not showing the terminal when called.
 
 
 On Linux :
 Put the .py files in the home folder and run `chmod +x pythonScript.py` to allow its execution. Then you can run it with `./pythonScript.py`
 
 
# Scripts

## Ideas

 * Multiclipboard : can have more than one single string in the clipboard. Could have different way to handle that and make it really practical. Could be simply ordered and use the number to call it. Could first launch the program, then `Ctrl+C, <anykey>` to copy with keyword, and similar for pasting the correct one. Could show a window to show which are the things in the . Could have a way to delete a word from the clipboard.
 

* Handle time differences with france/tw/brazil (among others). I just want to easily make sure that at X in Y place, it will be X' in Y' place. *Note : could be made into a simple website*

* Transform a website into pdf/epub ebook (should already exist)

## Done


# Could be useful

* Windows *Hooks* : (https://msdn.microsoft.com/en-us/library/ms644959%28VS.85%29.aspx?f=255&MSPPError=-2147217396#wh_keyboard_llhook)

* Last chapters of [*Automate the Boring Stuff with Pyhton*](https://automatetheboringstuff.com/)

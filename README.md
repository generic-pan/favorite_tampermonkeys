# Favorite Tampermonkey Scripts
My favorite Tampermonkey scripts, which reduce repetition in my workflow by at least 30%

### Auto-Copies When Select (wChenonly)
[Link](https://greasyfork.org/en/scripts/469846-select-to-copy/code)

Automatically copies whenever you select text

### Workaround for Google I'm Feeling Lucky Redirect (Qria)
[Link](https://greasyfork.org/en/scripts/390770-workaround-for-google-i-m-feeling-lucky-redirect)

Removes redirect when using "I'm Feeling Lucky Shortcut"

## Other Automations/Optimizations

### Pin VSCode Folder to Windows Taskbar
1. Create a .bat file with the code
```
@echo off
code C:\YOUR_FILEPATH
```
2. Create shortcut from the .bat file
3. Change shortcut target in "Properties" to `%ComSpec% /c BAT_FILEPATH`
4. Pin shortcut to taskbar
5. Bonus:
> And if you're annoyed that a cmd window pops up every time you use the shortcut, after pinning, you can open the shortcut at C:\Users\<User name>\AppData\Roaming\Microsoft\Internet Explorer\Quick Launch\User Pinned\TaskBar and change the target path back to path-to-your-batch – 
apple16

### Quick Tab Switch
[Link](https://chromewebstore.google.com/detail/shortkeys-custom-keyboard/logpjaacgmcbpdkdchjiaagddngobkck)

Then, go to [Chrome extension settings](chrome://extensions/shortcuts) and set Ctrl+Q for Previous Tab

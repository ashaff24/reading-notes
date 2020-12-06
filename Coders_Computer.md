## Text Editors
- Examples
  - Microsoft Word
  - Google Docs
  - Apple Pages
  - ...many more

## Code Editors
- Personal choice
- Allows you to write and manage text that you write to build a website
- Attributes to look for when choosing:
  - Code Completion
    - Start typing, give suggestions
    - Automatic tag closing
    - Emmet - shorthand language (built in or extension), speeds up code writing
  - Syntax Highlighting
    - Hightlights the text you type, making it more noticeable
    - Easier to read
    - Easier to find errors
  - Variety of Themes
    - Reduce eye strain and fatigue
  - Selection of extensions
    - Can grow with you as you need
- Examples
  - GitHub's Atom
  - Microsoft VS code, Visual Studio
  - Notepad ++
  - Vim, EMacs, Nano, Textmate
  - ...many more

### **Built-In vs Third Party:**
#### Built in
- Not many features to speak of
- Bare bones

#### Third Party
- Options mentioned above
- Visual Studio Code
  - What we downloaded
  - Has Emmet shorthand for HTML and CSS
  - Has all features mentioned above

### IDE (Integrated Development Environment)
- All in one
  - Text editor
  - File manager
  - Compiler
  - Debugger
- Example: Microsoft Outlook

## The Terminal
AKA: The Command Line Interface (CLI)
Basically does the same thing as File Explorer but in a different visual presentation
When you use File Explorer, terminal tasks are actually running behind the scenes

### Examples of commands in Terminal:
- ls = lists all files/folders in directory
- mkdir = make directory
- cd = change directory
- cd .. = go back one directory
- touch = create new file

### Terms
- Prompt: mine is amanda$, this shows its ready for you to type. After command has run and terminal is ready for you, prompt will be displayed
- Command: first thing you type
- Option (also First Command): used to modify behavior of command. Typically starts with a dash. Has to be a space between Command and Option
- Output: what results from running the command (some commands don't display anything unless there is an error)
- Shell: defines how terminal will behave and look
   - most common is bash (Bourne again shell)

### Basic navigation:
- pwd: Print Working Directory (verify where we are)
- ls: list (what's our current location)
- Whenever we refer to a file or directory on the command line, we are using a path
- File system under Linux is hierarchichal 
  - Top of structure is **root** directory, denoted by a slash (/)
  - Relative paths specify a location in relation to where we currently are and do not begin with a slash
  - ~ : home directory
  - . : reference to current directory
  - .. : reference to parent directory (use to go up hierarchy)
- Can refer to a location in a variety of ways
- cd: change directory (used to move around)
- Tab completion: when you start typing a path, you can hit Tab and it will invoke auto-complete
- Relative path: a file or directory location relative to where we currently are in the file system
- Absolute path: a file or directory location in relation to the root of the file system

### Misc Linux Info:
- Everything under the hood is a file (text file, directory, keyboard, monitor, etc)
- Linux ignores file extensions and looks inside the file to determine what type it is
  - Can use **file** to find out what kind
- Linux is case sensitive
- If there are spaces in file names, put quotes (single or double) around entire name or use a backslash (\) which denotes escape characters
- . = hidden file
  - ls will not list hidden files/directories by default, but can modify it by adding in -a to show hidden files

## Layers of Abstraction
- You won't necessarily know what's happening above or below you
- Ignore those details that are above or below you
![Layers of Abstraction](Layers_of_Abstraction.jpg)

[<== Back](README.md)


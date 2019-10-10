---
topic: "vscode"
desc: "Visual Studio Code, a lightweight free editor from Microsoft with many IDE features"
---

# How to get it

* On CSIL, type `code` to access the VS Code editor.
* For your own machine, download it from here: <https://code.visualstudio.com/>

# Customizing it

You'll likely need to add some "extensions" for the programming languages that you want to use (Java, C++, etc.)

# Tips and Tricks

* Multiline Editing: (copied [from here](https://stackoverflow.com/a/30039968))
   * On Windows, you hold Ctrl+Alt while pressing the up ↑ or down ↓ arrow keys to add cursors. 
   * On Mac, ⌥ Opt+⌘ Cmd+↑/↓
   * On Linux, Shift+Alt+↑/↓

# Mac OS Specific

On MacOS, if you want to be able to type `code .` at the Terminal command line
to open vscode in the current directory, here's what you need to do:
* Open the Command Palette (⇧⌘P) and type `shell command` to find the `Shell Command: Install 'code' command in PATH command` option
* Select that option, and behind the scenes, it will do the needed stuff to update your path.
* You will need to open a new Terminal window to see that take effect.
* Source: <https://code.visualstudio.com/docs/setup/mac>

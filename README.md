Sublime JavaScript Scratch Pad
=========================
Try out JS right from Sublime

## Requirements

Needs the NodeJS **node** command to be available in the shell PATH and that's about it
for trying out vanilla JS. If you need to include external JS libs, you can configure them
in the plugin settings.

## Installation

To install it **manually with Git:** Clone the repository in your Sublime Text 3 Packages directory:

    git clone https://github.com/bijoythomas/sublime-ramda-repl ramdarepl


The "Packages" directory should be located at:

* OS X:

    ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/

* Linux:

    ~/.Sublime\ Text\ 3/Packages/
    or
    ~/.config/sublime-text-3/Packages/

* Windows:

    %APPDATA%/Sublime Text 3/Packages/


The plugin should be picked up automatically. If not, restart Sublime Text.

## Usage

Use the **JS Scratch Pad** Sublime command to open a scratch pad in Sublime.
![Screenshot](https://github.com/bijoythomas/sublime-jsscratchpad/raw/master/plugin_command.png)


Type in your JS code and hit **ctrl+shift+r** to run it.

The plugin adds the following key bindings.

```
[
  {
    "keys": ["ctrl+shift+r"], "command": "js_scratch_pad"
  }
]
```

## Settings

You can tweak the plugin settings to provide the path to the node modules dir and
how you would like to access the imported libs in the scratch pad

```
{
  "node_modules_path": "/Users/me/project/node_modules",
  "libs" : {
    "ramda": "R", // access ramda functions with the R. prefix
    "moment": "moment", // access moment functions with the moment. prefix
    "q" : "Q" // access Q library functions with Q. prefix
  }
}
```

## Screenshot

![Screenshot](https://github.com/bijoythomas/sublime-jsscratchpad/raw/master/screenshot.png)



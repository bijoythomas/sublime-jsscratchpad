Sublime JavaScript Scratch Pad
=========================
Try out JS right from Sublime

Requirements
============
None if you are trying out vanilla JS. If you want to play with JS libs, simply
edit the pluign settings

Installation
------------
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

Usage
-----
Simply use the JS Scratch Pad command to open a new tab in Sublime, type in your JS code
and hit ctrl+shift+r

The plugin adds the following key bindings.

```
[
  {
    "keys": ["ctrl+shift+r"], "command": "js_scratch_pad"
  }
]
```

You can tweak the plugin settings to provide the path to the node modules dir and
how you would like to access the imported libs

```
{
  "node_modules_path": "/Users/me/project/node_modules",
  "libs" : {
    "ramda": "R",
    "moment": "moment",
    "q" : "Q"
  }
}
```

Screenshot
---------
![Results](https://github.com/bijoythomas/sublime-jsscratchpad/blob/master/screenshot.png)

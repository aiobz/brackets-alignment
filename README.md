## brackets-Alignment for [Brackets](http://brackets.io)

[Brackets on GitHub](https://github.com/adobe/brackets)

This [Brackets](http://brackets.io) extension allows you to make some beautiful code alignments of object literals and variable assignments.Base from [Align It!](https://github.com/ggarek/brackets-extension-alignit).

### Installation
* Select **File > Extension Manager**
* Click **Install from URL**
* Enter the url of this repo: 
 * https://github.com/zhaopengme/brackets-Alignment
* Click **Install**


### How To Use
1. Make selection of code range you want to align in the editor
2. Press **"Ctrl+\"** hotkey or go to **"Edit->Align It"** menu item
3. The magic has happend! ^__^

### Usage examples
#####Example #1:
This code snippet:

    var AppInit = brackets.getModule("utils/AppInit"),
        CommandManager = brackets.getModule("command/CommandManager"),
        EditorManager = brackets.getModule("editor/EditorManager"),
        Menus = brackets.getModule("command/Menus");

will be transformed to:

    var AppInit         = brackets.getModule("utils/AppInit"),
        CommandManager  = brackets.getModule("command/CommandManager"),
        EditorManager   = brackets.getModule("editor/EditorManager"),
        Menus           = brackets.getModule("command/Menus");


#####Example #3:
This code snippet:

	var a = "hello",
	    abc = "forget it",
		isCanceled = false,
		emptyObj = {};

will be transformed to:

	var a 			= "hello",
	    abc 		= "forget it",
		isCanceled 	= false,
		emptyObj 	= {};

#####Example #2:
This code snippet:

	var a = {
	 id : 1,
	 name : "skull",
	 tags : [ "cool", "dark" , "mysterious"],
	};

will be transformed to:

	var a = {
	 id 	: 1,
	 name 	: "skull",
	 tags 	: [ "cool", "dark" , "mysterious"],
	};

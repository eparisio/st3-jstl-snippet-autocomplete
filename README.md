# sublime text JSTL snippet and autocomplete attribute
Basic support for sublime text jstl autocomplete of the standard core libs costructor plus some non-core libs (spring)

#### Info
* jsp/tag file support
* fn, x, sql, fmt, c, spring, sec, pe, tiles tags support
* autocomplete for parameters not present in the base snippets

start to digit one of the above taglib to view all tags associated to it.

jstl comment snippet, add a shortcut to your key-binding user file:

```{ "keys": ["ctrl+alt+q"], "command": "insert_snippet", "args": { "name": "Packages/YourPath/jstl-comment.sublime-snippet" } }```

where "YourPath" is the installation directory if you install it manually, than set the keybind as you want


#### Installation
##### Using Package Manager

The easiest way to install is to use the Package Control extension. Once this is installed, simply select 'Package Control: Install Package' from the command pallette and search for 'JSTL autocomplete'.

##### Manually

Within Sublime Text, click Preferences > Browse Packages... and create a folder named JSTL-snippet. Clone this repo or add the files into the folder.

#### develop note:
* highlight JSTL syntax: https://github.com/eparisio/st3-jstl-syntax-highlight , from package control: JSTL syntax highlight
* if i miss some tag or there is some error please open an issue
* credits to https://github.com/JeroenVdb/jstl-sublime-snippets for starting the works, i have resolved some errors and added all the missing tags and libs, plus added to package control

### TO DO:


### Contribute

If you want contribute follow the project at: 

* https://github.com/eparisio/st3-jstl-snippet-autocomplete

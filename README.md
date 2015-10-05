# sublime text JSTL and JSP syntax highlight
Basic support for sublime text jstl and jsp syntax highlight.

Based on original Java Server Page(JSP) syntax highlight.

#### File support
* jsp
* tag

#### Installation
##### Using Package Manager

The easiest way to install is to use the Package Control extension. Once this is installed, simply select 'Package Control: Install Package' from the command pallette and search for 'JSTL syntax'.

##### Manually

Within Sublime Text, click Preferences > Browse Packages... and create a folder named JSTL. Clone this repo or add 'jstl.tmLanguage' file into the folder.

#### develop note:
* highlight __all__ jstl base tags(```<xxx:xxx>```), parameter in the tag(```xxx="```) and server variable(```${}```)
* ~~add support for all jstl tag~~ - added general regex for __jstl tags and custom tags__
* ~~review regex for highlight end-closing tag with parameter~~ - added support and internal text highlight
* ~~add highlight for jstl operation inside tags (and,or,<,>,eq,ne,=,etc)~~  - add highlight for operator, add highlight for jstl functions
* add highlight support for all base color scheme

### TO DO:
* ~~add support for all jstl tag~~
* ~~review regex for highlight end-closing tag with parameter~~
* ~~add highlight for jstl operation inside tags (and,or,<,>,eq,ne,=,etc)~~
* ovverride html syntax color in normal html tag for nested tags/server var

### Contribute

If you want contribute follow the project at: 

* https://github.com/eparisio/st3-jstl-syntax-highlight

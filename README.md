![screenshot](https://raw.githubusercontent.com/stanleyseow/DarkArduinoTheme/master/screenshot.png)

Dark Arduino Theme
================

Revised for Arduino version 1.6.6+, not tested with earlier versions.

\- \- \-

### INSTALLATION
Mac users should look in `~/Applications/Arduino.app/Contents/Java/lib` and replace the `theme` folder inside (making a copy of the original in case want to revert back). Windows is located in `C:\Program Files (x86)\Arduino\lib`.

### CREATING YOUR OWN MODS
The newest version of the Arduino IDE makes creating custom themes trickier: you now need to edit the `theme.txt` file, an XML file inside the `syntax` folder, and the button files. Unfortunately, not all items in the `theme.txt` file actually work, so if you can't get an item to change, try another one of the files.

### Basic Documentations on the colours

I use HTML colour picker to find out what colors does what ...
https://www.w3schools.com/colors/colors_picker.asp

This is what I found by trial and errors :-

**TEXT - KEYWORDS FUNCTIONS** 
Orange, 60% 

`editor.keyword1.style = #FFAD33,bold`
`editor.data_type.style = #FFAD33,bold`

**METHODS**
Orange, 60%

`editor.keyword2.style = #FFAD33,plain`
`editor.function.style = #FFAD33,plain`

**STRUCTURES**
Reserve words ( loop, setup, while )
Dark green, 50%

`editor.keyword3.style = #D8F906,plain`
`editor.reserved_word.style = #D8F906,plain`


**Built-in variables, literals, reverse words, data types**
Light blue, 31%

`editor.literal2.style = #00979C,plain`
`editor.variable.style = #00979C,plain`
`editor.reserved_word_2.style = #00979C,plain`
`editor.literal_boolean.style = #00979C,plain`
`editor.literal_char.style = #00979C,plain`

**Preprocessors** (#ifdef, #defines, #endif)  
Blue, 60%

`editor.preprocessor.style = #3399ff,plain`

**Comments colours**
Grey, 67%

`editor.comment1.style = #aaaaaa,plain`
`editor.comment2.style = #aaaaaa,plain`

**Selection area**
Light grey, 25%

`editor.selection.color = #404040`

**ToDo**

* Curly brackets
* Numbers ( currently yellow )
* Variable name ( currently white )



\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).

# arcview_editor
Editor is an Avenue extension used in ArcView GIS that provides many useful tools for editing shapefiles and graphic text features. 

## Purpose
![Editor toolbar](https://github.com/ABoehlen/arcview_editor/blob/main/editor_toolbar.png)

Editor includes tools for convenient editing shapefiles and graphic text elements. There are 5 groups of tools:
* General editing tools: Tools such as start editing, select and edit attributes
* Create feature tools: Tools for creating point, line and polygon features
* Modify features tools: Tools such as reshape, merge, rotate etc. 
* Edit text tools: Tools for creating and editing graphic text elements
* Various tools: Refresh view and reload default values

## Background
ESRI's ArcView GIS is a rather old (1995 – 2002), but for many purposes still useful GIS application. Due to its age it's very fast on modern hardware and has full support for the still widely used vector data format _Shape_ (SHP).

Avenue is ArcView's built-in object oriented scripting language. "By using Avenue, you can customize the program and further extend its power", describes Amir H. Razavi the language's purpose in his 1999 book \[1\].

## System requirements
An ArcView GIS 3.x installation is required.

## Installation
Download the repository into your desired directory:

```
cd <directory>
git clone https://github.com/ABoehlen/arcview_editor
```

* Copy Editor.avx into the ext32 directory of your ArcView installation.
* Copy default_values.dbf into a directory of your choice if it doesn't exist already. The same file is used by https://github.com/ABoehlen/arcview_layout_tools
* Open ArcView GIS with a new empty project or with an existing one.
* Choose File –> Extensions
* Turn on the Extension Editor and close the Extension dialog again.
* In the View documents open an existing view or create a new one.
* In the button list of the View document GUI click on the new button "Start Editor toolbar". The toolbar should open. As well opens the dialog where you have to select the default_values.dbf table file.

## License

This project is licensed under the MIT License - see the LICENSE file for details

***

## Literature
\[1\] Razavi, Amir H.: ArcView GIS Developer's Guide, 1999

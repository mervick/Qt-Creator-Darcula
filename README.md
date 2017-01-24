QT Creator dark theme
=====================
The darkness color scheme "Darcula" (based on Darcula IntelliJ Theme) for Qt Creator and syntax highlighting theme. 

Usage
-----

1. The stylesheet `darcula.css` defines color scheme for the Qt Creator GUI.  
Can be loaded with the `-stylesheet` parameter on startup of Qt Creator.  
  Example:
  ```
  qtcreator -stylesheet=/path/to/stylesheet/darcula.css
  ```
  
2. Colorscheme file `darcula.xml` which defines the colors for syntax highlighting. This file should be copied into the styles directory of Qt Creator.
On linux the path to this directory is `~/.config/QtProject/qtcreator/styles`.

3. The color scheme use some images for the GUI elements. So, directory `images` must be located in the same directory with the file `darcula.css`.


Enjoy coding!

Previews
--------
![Options Dialog - Screenshot](https://raw.githubusercontent.com/mervick/Qt-Creator-Darcula/master/previews/screen1.png)
![Analyze - Screenshot](https://raw.githubusercontent.com/mervick/Qt-Creator-Darcula/master/previews/screen2.png)

# TDL-coloring ( ⚛ package)
Atom package that adds basic support for TDL (Type Description Language) syntax. This means accurate syntax highlighting/font locking when editing DELPH-IN-style `.tdl` and `.mtr` files, provided the conventions described in *Implementing Typed Feature Structures* (Copestake 2002) are followed. 

### Note to users

This package was thrown together in an afternoon and has been refined (lazily, and to the best of my ability) based on my own needs while working within a predominantly LinGO Matrix-based framework. Should you encounter unexpected or annoying behaviour, yet wish to eschew Emacs (in spite of the all-powerful *tdl-mode* Emacs package that ships with all standard LKB installations), feel free to leave a suggestion anywhere on this repository. Other contributions are of course welcome, too! :) 

### The `[ <-- space --> FEATURE` gotcha 

In order for the regex parser to work properly, opening square brackets are required to be seperated from enclosed feature names by one or more spaces. This may be changed in a future update, although there's no ignoring that it does have the happy side-effect of making grammar descriptions easier to read. 

### Screenshots

*NB*: Frustratingly easy to forget yet essential to successful compilation, **commas and periods** are now highlighted as well. 

dark                                                                                          | light
:--------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------
![](https://raw.githubusercontent.com/lemontheme/tdl-coloring/master/screenshots/dark_tdl.png) | ![](https://raw.githubusercontent.com/lemontheme/tdl-coloring/master/screenshots/light_tdl.png)

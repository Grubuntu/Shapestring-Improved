# FreeCAD ShapeString Font Preview Macro

## 📝 Description

This FreeCAD macro provides a graphical interface to preview, select, and apply system fonts (TrueType or OpenType) with their full styles (e.g. Bold, Italic, Bold Italic) to `ShapeString` objects in the 3D view.

It uses the `fontTools` library to read detailed font metadata, such as full name and style, and the Qt font system to dynamically apply the correct visual appearance in the interface.

## 🎯 Features

- Edit existing shapestring (select a shapestring and run the macro)
- Browse and preview all installed fonts.
- Fonts are displayed in their actual style (Bold, Italic, etc.) in a drop-down list.
- Live preview of your custom text with the selected font.
- Set the text position, size, rotation, and alignment.
- Create or update a `Draft ShapeString` object in the FreeCAD document.
- Expression support for position and size parameters.
- Full Unicode support.
- Support color

## 🛠 Requirements

- FreeCAD (tested with versions supporting PySide6)
- Python module `fontTools`  

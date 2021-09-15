# NIXIE_TUBE_for_Unity

This is a nixie tube that can be used in Unity.
This is the default rendering pipeline, so you will need to do a material conversion if you want to use it in URP or other applications.

A sample scene is included, so please use it as a reference.

## Specifications
A total of 14 characters can be displayed, including single-byte characters from '0' to '9', 'blank', "#", "-", "/", ". ." etc. can be displayed.

There are two display methods, which can be changed from the "Inspector view".
"Defult" switches the display of the object and executes it.
The "material_mode" setting blackens the material of objects that are not displayed, and lightens the material of objects that are displayed,
"material_mode" darkens the material of non-displayed objects and lightens the material of displayed objects.
The "material_mode" mode increases the reality, but at the same time makes it more difficult to see.

The developers recommend "Defult" because it makes the visible objects more visible.

## How to use

1,Place "NIXIETUBE" in the scene from /prefab.

2,Create an empty object and attach "improvement_NIXIEManager" from /Script.

3, Register an arbitrary "NIXIETUBE" and a numerical value to "improvement_NIXIEManager".
The digits of the numbers are displayed in the order in which they were registered.

4,Ready to run

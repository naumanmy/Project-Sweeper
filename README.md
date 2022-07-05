Edited by Ryan Puett 2022.01.23 to function with 2022 ForgeId/SpecId units.  See Comments
Edited by David B 2022.07.04 
     Updated references and pkhCommon seemed to get it working.  Need to test functionality and I still don't understand the build method. 
# Project-Sweeper

Project Sweeper is a collection of tools that allow a user to quickly and accurately remove the following clutter from Revit projects:
  line styles
  line patterns
  text styles
  fill region types and
  fill patterns.
Except for text styles, these items are not checked by Revit's "Purge Unused" command. Project Sweeper goes beyond just checking for unused styles and patterns. 
It also allows a user to convert from one style\pattern to another, delete all the elements using a style\pattern and to preview all the views\elements using a 
style\pattern before removing it.

Refer to html_help_files.zip for detailed description of what each command does.

Make sure you also download the project "pkhCommon_strongNamed", it has utility functions that this project uses.

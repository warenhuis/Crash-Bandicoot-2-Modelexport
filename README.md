# Crash-Bandicoot-2-Modelexport
This is an unofficial and experimental tool for exporting models of Crash Bandicoot 2 and possibly Crash Bandicoot 3 in the future. For now, the tool is very primitive and written in the free edition of GameMake 7.0, depends on CrashEdit and only works for models that consist out of 5 items.

Usage:

0. Download CrashEdit if you don't have it already (github.com/ughman/CrashEdit)

1. Download the ZIP (this repository) and extract the ZIP in a directory
2. Think of what model you want to extract. Create another directory inside the directory for that model, for example "penguin".
3. Using CrashEdit, export one animationframe and the corresponding 5 items of the model that you want to export to the same directory. They must have the following names:
  - "frame"
  - "item0"
  - "item1"
  - "item2"
  - "item3"
  - "item4"

4. Run CB2Export.exe You are asked for the foldername, type in the directory for your model - for example: "penguin" (without the quotes) After this you can see the data for the model if you are interested.
5. Press Enter and give up the filename, press 'OK'
7. Enjoy your model!

The tool works far from perfect as of yet, important future improvements include:
- More accurate vertexcoloring
- More accurate UV mapping
- 6-item model support

New findings and suggestions are always welcome, so feel free to make a new issue on this repository

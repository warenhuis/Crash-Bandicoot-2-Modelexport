# Crash-Bandicoot-2-Modelexport
This is an unofficial and experimental tool for exporting models of Crash Bandicoot 2 and Crash Bandicoot 3. For now, the tool is very primitive and written in the free edition of GameMaker 7.0 and depends on CrashEdit.

Usage:

1. Download CrashEdit if you don't have it already (github.com/ughman/CrashEdit)

2. Download the ZIP (this repository) and extract the ZIP in a directory
3. Think of what model you want to extract. Create another directory inside the directory for that model, for example "penguin".
4. Using CrashEdit, export one animationframe and the corresponding 5 items of the model that you want to export to the same directory. They must have the following names:
  - "frame"
  - "item0"
  - "item1"
  - "item2"
  - "item3"
  - "item4"
  - "item5" (only if it exists)

5. Run CB2Export.exe You are asked for the foldername, type in the directory for your model - for example: "penguin" (without the quotes) 
	After this you must specify wether it is an Crash Bandicoot 2 or Crash Bandicoot 3 model, typing "2" or "3"
	After this you can see the data for the model if you are interested.
6. Press Enter and give up the filename, press 'OK'
7. Enjoy your model!

New findings and suggestions are always welcome, so feel free to make a new issue on this repository

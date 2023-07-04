# Adding a Character
An RPG isn't much fun without any characters. All of the characters that you will track in the game will be stored in the Characters directory. To add your first character copy the Blank Character directory into the Characters directory. Change the name `Blank Character` to the name of your character. 
## Character files
Each character consists of several files. All of the files that begin with an underscore are smaller sections of the character sheet and are included into the main character file. This is done to make it easier to edit individual parts of the character but also, as you will see later, to let you display those sections on their own in individual panes. 

Change the name of the file `New Character.md` to match the name of the directory it is in. So if your character is called 'Atalantia' then the directory should be named `Atalantia` and the `New Character.md` files should be renamed to `Atalantia.md`.

The chartacter file has a small amount of actual text in it and instead includes several files to create a larger document when you view it in Preview mode. There are two reasons for this. First, it keeps the main character document clean and easy to edit and easy to not accidentally edit. Secondly, this allows you to display those included files in separate panes in Obsidian. We'll look at that later. 

### Stats
The `_Stats.md` file contains a table with the five stats for your character. The file also contains some metadata in YAML format that you can ignore for the time being. Edit the table and change the numbers in the Value column to match your character's stats. The third column in the table has settings for the Dice Roller to allow you to click on it and generate a D6 + stat roll during play. Change the values in the code block, the characters between the \` \` characters to match your stats. 
### Tracks
The `_Tracks.md` file contains a table that have other important character information that you need to access during gameplay. These are currently set to the defaults for a new character. The number in brackets after the Maximum value for Momentum is the current Reset value. 
### Vows
The `_Vows.md` file contains a series of table rows that you can use to track the status of the Vows that your character starts out with and any that they add during your campaign. The Vows file has several blank rows that you can use to write out your initial Vows. If you need to add more you can use the `Vow Table Row` template to add a new one. 

Each Vow has a place for a name, a set of progress markers and a space to write down the Difficulty of the Vow. 

### Assets
The `_Assets.md` file is a place to store Assets that you pick for your character during character creation and that you add by using Experience. You can find the Assets for Ironsworn in the [[Assets]] file in the Rules directory. The Assets file is included into your main character file to keep that file simple and easy for you to edit without worrying about all of the data and text that accompanies each Asset.

### Progress
The `_Progress.md` file is used to track the progress of any tasks or combats that your character is involved in. The format is the same as the Vow tracker and there is also a `Progress Task Row` template you can use to add new rows to the table.

Next up is to determine your stats and  [[Recording Details|then record them]]. 








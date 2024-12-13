# Custom-Roleplay-Data

This is a custom datapack for testing minecraft item textures

## Usage

A datapack that allows you to easily change the CustomModelData of items to change the look of items using resource packs.

To change the model data of an item stack in the player's mainhand:

´´´
/trigger CustomModelData set <model data #>
´´´

You can change the XP required cost of this action by doing:

´´´
/function custom_roleplay_data:admin
´´´

to access the admin menu or by using the command:

´´´
/scoreboard players set #min_level crd_xp_dummy <level>
´´´

## Installation

Data Packs and Crafting Tweaks
Click on "Single Player" in the Main Menu.

Find the world where you want to install the Data Packs/Crafting Tweaks, select it and press "Edit".

Click on "Open World Folder" in the Settings menu.

Go to the "datapacks" folder.

Move the file you downloaded to that folder. (Crafting Tweaks skip to step 9.)
Data Packs only:

Right click the zip file and click "Extract All". Press "Extract"

It should open a new window with the datapacks you selected.

Move all the files to the same folder where the .zip file is located. (CTRL+A to select all files)

Delete the "UNZIP_ME" folder and file.

You have now successfully installed the datapacks and crafting tweaks into your world!
You may have to run "/reload" in your world if it is already open

## License

[MIT](https://choosealicense.com/licenses/mit/)
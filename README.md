# ConvertFrog
GUI for my handbrake/mediainfo batch script for converting specific video files within a mixed directory.

# UPDATE: GUI NOW HERE!!
I added a simple XML-Based GUI to the batch script using FroG (Frontend Generator). In the folder is everything needed to run the GUI, including a copy of frog.exe. Download entire "ConvertFrog" folder to use.

To launch the GUI, start the "ConvertFroG" shortcut.

You'll be able to set Source and Destination folders via browse folder. Currently *5* MediaInfo parameters are available (BitRate, Width, Height, Framerate, Filesize; more to come). 6 comparison operators are available. You can manually set the value to compare. And lastly, most of the handbrake encode settings are available for manual edit. I plan on GUI'ing this secton but there are a lot of options for handbrake. Refer to HandbrakeCLI FAQ to learn to edit this code. I'll attach printouts of handbrake/mediainfo parameters/help.

# YOU MUST DOWNLOAD MEDIAINFO AND HANDBRAKE COMMAND LINE INTERFACES AND COPY TO /BIN FOLDER.

## Update 2:
Script is as done as it's going to be. The interface (frog) doesn't have enough power to make a proper GUI for the handbrake settings. I feel leaving it as CLI would provide more flexibility. Updated icon & banner and officially named the GUI "ConvertFroG".

## Screenshots of Interface
![Page 1](https://github.com/j0ckinjz/Batch-Convert-Script/raw/master/imgs/CFtab1.PNG)
![Page 2](https://github.com/j0ckinjz/Batch-Convert-Script/raw/master/imgs/CFtab2.PNG)

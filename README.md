# Just-Cause-3-Key-Bindings-Fix

## Assumptions
The game is installed using Steam.  Other services might store the game data at this location.  You will need to find where the file kepmap.txt file is located and modify the script. 

## Definitions
USERNAME: The name of the user account that you play Just Cause 3\
saved_data_dir: The name of the directory where your saved data is located.  It is a 16 digit integer value.

## Instructions
1. Copy/Clone the project to a location that you can easily remember.  Make sure you are logged into the account that you use to play Just Cause 3.
2. Open the file Copy_Key_Map.bat file in a text editor
3. Navigate to C:\Users\USERNAME\Documents\Square Enix\Just Cause 3\Saves\.
4. In the Saves directory you will find a directory represented as a 16 digit integer.  Copy the name of this directory.
5. Inside the Copy_Key_Map.bat file replaced the variable saved_data_dir with the string.  Removed the arrows and make sure there are no spaces after the equals sign.

&emsp;&emsp;Example\
&emsp;&emsp;Before: set settings_dir=<saved_data_dir>\
&emsp;&emsp;After: set settings_dir=76561199157138841

6. When starting new game run the script within 10 seconds of selecting a new game in the menu.

## Stream Deck Instructions
1. Under System drag the Open action to your layout.
2. Create a title that you find useful.
3. Within the App / File: input paste the location to the script within quotes.
4. Test to make sure your new action works as required.



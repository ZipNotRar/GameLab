# Krugerspoof
## The files presented here show the logic behind production of the detective thriller 2D game "Krugerspoof":-

* The [**MEAccuracy.cs script**](ComfyStudiosGameLab/Assets/Scripts/MEAcurracy.cs) uses if else conditions with adding numbers until a certain number is reached to unlock areas for player so that they can move through the story AND level itself. While doing so, a slider bar is attached to the number generateion to debug the conditions being met quickly.
* The [**CameraResolution.cs script**](ComfyStudiosGameLab/Assets/Scripts/CameraResolution.cs) rescales the camera based on the size of window itself. On gathering the screen's width and height, the width and height of player's camera is adapted. This is done on every frame as well. 
* The [**Inventory.cs script**](ComfyStudiosGameLab/Assets/Scripts/Inventory.cs) creates an list of gameobject based on an array system and assigns a bool to that list.
* Finally, the [**Pickup.cs script**](ComfyStudiosGameLab/Assets/Scripts/Pickup.cs) gives the player feedback if the item they picked to solve a part of the crime (possible the murder weapon) is the correct item or not, if not, then the inventory slot gets highlighted as red. This script accesses the data within the  **Inventory Script's** list to check whether any item collected represents the "correct" item within the list or not.

## If you'd like to play the game, please follow these instructions:-
1. Download the **Executable** folder.
2. Double click on the [**Executable file**](Executable_File/ComfyStudiosGameLab.exe) and you will be in the main menu screen.
3. You move around with mouse clicks and can explore the area around you until you get to your first object which then starts the story of a mysterious murder that took place in the city you are playing in-game.
4. Enjoy the show!

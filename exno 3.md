EXP-03: Change the Third Person Character Mesh and Add Animations.
Aim:
To Change the third-person character mesh and add animations
Procedure:
1: Prepare your new character mesh and animations:
2: Create or import a new character mesh with its associated skeleton.
3: Make sure you have animations for your character, such as idle, walk, run, jump, etc.
These animations should be compatible with the new character mesh and have the same
skeleton hierarchy.
4: Open your project in Unreal Engine Editor.
5: Locate the Third Person Character Blueprint:
6: In the Content Browser, navigate to the folder where your Third Person Character
Blueprint is located. By default, it's usually located in the "Blueprints" folder.
7: Open the Third Person Character Blueprint:
8: Double-click on the Third Person Character Blueprint to open it in the Blueprint Editor.
9: Replace the character mesh:
10: In the Blueprint Editor, select the existing character mesh component (usually named
"Mesh").
11: In the Details panel on the right-hand side, find the "Skeletal Mesh" property.
12: Click on the dropdown arrow next to "Skeletal Mesh" and select your new character
mesh. Configure the character skeleton:
13: If your new character mesh has a different skeleton from the default Third PersonCharacter
Blueprint, you need to set up the new skeleton.
14: In the Details panel, find the "Animation Mode" property and set it to "Use Animation
Blueprint."
15: Click the dropdown arrow next to "Animation Blueprint" and select or create an
animation blueprint matching your new character's skeleton.
16: Assign animations to the animation blueprint:
17:18: Inside the animation blueprint, you can set up the animations for your character.
19: Find the "Animation" section or graph, and add animation nodes for each animation you
want to use.
20: Configure the animation nodes with the appropriate animations for your character. 21:
Save your changes: Save the Third Person Character Blueprint and the Animation
Blueprint.
22: Test the character: Close the Blueprint Editor and go back to the main Unreal Engine
Editor.
23: Play the game or simulate it to see the changes you made to the character.:
Output:

![Screenshot 2025-05-14 133700](https://github.com/user-attachments/assets/b429db2a-bfc7-47f9-9fd0-aa9a31af3c5f)

![Screenshot 2025-05-14 133719](https://github.com/user-attachments/assets/ad97f290-2206-47b7-9e14-3f77610e08fd)

![Screenshot 2025-05-14 133725](https://github.com/user-attachments/assets/70cb200b-a5c7-40e2-b408-786aacfefffa)

Result:
Changing the third-person character mesh and adding animations is implemented
Succe

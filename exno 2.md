# EXP-02: Create A Player Movement Using Pawn, Collectable, Player Health And Score.
## Date:
## Aim:
To Create a player movement using pawn, collectible, player health and score.

## Procedure To Create and Destroy the coin:
1.  Open Unreal Engine. Choose Games → Third Person template.Name the project (e.g., PlayerCollectSystem) and select Blueprint. 
2.  Navigate to: Content → ThirdPerson → Blueprints.  Open BP_ThirdPersonCharacter (your player Blueprint).  This character already has:Movement input,Mesh and 
 capsule,Camera. 
3. Create a New Blueprint Class:Right-click → Blueprint Class → Actor → Name it BP_Collectable. 
4. Add Components:Add a Static Mesh (e.g., sphere or coin mesh).Add a Sphere Collision around it.
5. Enable Overlap Events:In the Sphere Collision details:Set Collision Presets to "OverlapAllDynamic". Check Generate Overlap Events. 
6.  Blueprint Logic:Open Event Graph in BP_Collectable.Add OnComponentBeginOverlap (Sphere) event.Cast to ThirdPersonCharacter.If successful:Call a custom function 
 on the character to increase score or health.Then call Destroy Actor.
7. In BP_ThirdPersonCharacter: 
a. Add variables: 
i. Score (Integer) 
ii. Health (Float, default: 100) 
8. Create custom functions: 
a. AddScore(int Amount) 
b. AddHealth(float Amount) 
c. Inside these, update the respective variables.
9. In BP_Collectable: 
a. Add a boolean IsHealthItem. 
b. Add a float Value (e.g., 10). 
10. In the Overlap logic: 
a. If IsHealthItem is true → Call AddHealth(Value). 
b. Else → Call AddScore(Value). 
11.  Create Widget Blueprint:Right-click → User Interface → Widget Blueprint → Name it WBP_HUD. 
12.  Design the UI:Add Text widgets for:Health: Health: 100,Score: Score: 0,  3.Bind Text:Bind text to variables in ThirdPersonCharacter. 
13. In ThirdPersonCharacter, BeginPlay event: Create Widget (WBP_HUD). Add to Viewport. Store reference to update it later (optional). 
14.  Drag BP_Collectable into the scene.  Set different values for IsHealthItem and Value on each. 

## Output:

![image](https://github.com/user-attachments/assets/b42eb8dd-a385-44dc-a2ed-37ebb49b3cc9)

![image](https://github.com/user-attachments/assets/52646e30-9d0d-465f-81de-92c55fd1b085)

![image](https://github.com/user-attachments/assets/2bd8a09c-e170-4227-bf42-1ea6964846f0)

## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.

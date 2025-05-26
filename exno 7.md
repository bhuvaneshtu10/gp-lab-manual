    EXP: 07-AI CHASING
    Aim: To implement-chasing when AI see the player.
    Algorithm:
    STEP-1: Set up the AI character Blueprint and add a Sphere Collision component to the AI character Blueprint and position and scale the Sphere Collision component 
    to represent the AI's detection range.
    STEP-2: Create a new AI controller Blueprint and select Create Basic Asset > Blueprint Class from that choose the AIController as the parent class.
    STEP-3: Open the AIController Blueprint and drag off the execution line and search for "Set Sight Radius" where the Sight Radius value to the desired range for 
    the AI's vision.
    STEP-4: Implement perception for the AI and connect the output of the AI Perception Component node to the AI Controller's .AI Perception property in the AI 
    Perception Component node, configure the settings for sight and sight sense
    STEP-5: Implement the chase behaviour if the stimulus is the player character, drag off the execution line and search for "Move To Actor" and set the Move To 
    Actor node's target to the player character.
    STEP-6: Create blackboard keys for the AI and create a new blackboard object and assign it to the AIController's Blackboard property. Drag off the execution line 
    again and search for "Create Blackboard Key".
    STEP-7: Update blackboard values. Set the Blackboard Key to the "PlayerLocation" key you created earlier.
    STEP-8: Set up the Behavior Tree by Open the Behavior Tree asset in the Behavior Tree editor.

    Output:
![Screenshot 2025-05-15 214653](https://github.com/user-attachments/assets/e5f8c388-5784-4f1b-a34b-8b4beaa3aa3f)

![Screenshot 2025-05-15 214246](https://github.com/user-attachments/assets/004c8c9a-54b8-4757-9339-6404e6838b5f)

![Screenshot 2025-05-15 214526](https://github.com/user-attachments/assets/87b346af-b3b4-4014-ab43-7f47ad66f19a)

![Screenshot 2025-05-15 214535](https://github.com/user-attachments/assets/94409376-5cd7-4d55-a51a-8d221135a203)

Result:
Thus, the AI concept to the actor for a random movement

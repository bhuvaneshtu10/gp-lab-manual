    EXP-06: Implement the AI random movement.
    Aim: Implement the AI random movement.
    Algorithm:
    Step:01 Create a Character Blueprint.
    Step:02 Create a Blackboard.
    Step:03 Open the Behavior Tree editor.
    Step:04 Create Behavior Tree nodes for the following,"Selector" node: Controls the execution of child nodes."Service" node: Monitors and updates values in the 
    Blackboard."Sequence" node: Executes child nodes in sequential order."Random" decorator: Randomly selects a child node to execute."Move To" task: Moves the AI 
    character to a specified location.
    Step:05 Set up the Blackboard with vector key and bool keys and save it.
    Step:06 Set up the AI character Blueprint with the help of AI controller component.
    Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AICharacte Blueprint you created and drag off the AICharacter reference and search 
    for “Use Blackboard”
    Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to cover the desired play area.
    Output:

![image](https://github.com/user-attachments/assets/e8edce5a-4899-4b6a-97df-d5106c147e80)

![image](https://github.com/user-attachments/assets/4332d239-2043-44bc-81c8-28111bdd7fb6)

![image](https://github.com/user-attachments/assets/07dfa21d-046b-4e8e-99f4-f7a4ab83e05d)

![image](https://github.com/user-attachments/assets/880e4af5-6734-4730-bc39-0df87a66efe7)

Result:
Thus, the AI concept to the actor for a random movement is imple

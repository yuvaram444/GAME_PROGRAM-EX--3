# EX:3 Change the third person character mesh and add animations

### NAME  : YUVARAM S
### Reg No: 212224230315

## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure
1.Import New Character Mesh and Animations:
In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files).
Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).

2.Replace Character Mesh:
Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
Select the Mesh component.
In the Details Panel, change the Skeletal Mesh to the newly imported mesh.

3.Set Animation Blueprint:
If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
If not available, create one:
Right-click in the Content Browser → Animation → Animation Blueprint.
Choose the correct skeleton.
In the AnimGraph, set up state machines or direct animation nodes.
Compile and save.

4.Preview and Test:
Place the character in the level.
Press Play to test idle, walk, and run animations based on character movement.

## Output:

<img width="476" height="420" alt="image" src="https://github.com/user-attachments/assets/c476101c-d5e0-4809-b5e8-fdfe92528017" />

<img width="1541" height="912" alt="image" src="https://github.com/user-attachments/assets/f084e091-be57-4641-96ab-6dbcd237aafc" />

<img width="843" height="577" alt="image" src="https://github.com/user-attachments/assets/f5e177c8-a65d-4ba3-9c45-d9fa75011b01" />

## Result
Thus wehave successfully changed the third person character mesh and added animation.

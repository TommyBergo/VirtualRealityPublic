# VirtualRealityPublic
Public repository used for Virtual Reality exercises

This project is a small interactive VR scene built in Unity as part of the CS5970 - Virtual Reality course (Personal Assignment).

The scene represents a simple room environment (evening + restroom) where the user can move around and interact with several objects, following the instructions provided by the professor.

The project satisfies the following requirements:
- Setup of Unity XR Interaction Toolkit with OpenXR
- Two locomotion modes: teleportation and smooth movement
- Floor with at least 20 meshes on it. At least 10 of them have a PBR texture. 
- 6 lights in total. 5 realtime lights (1 of them is directional) + 1 baked light (optional point)
- 3 different interactable object with 3 corresponding sockets.

Set-Up Infomrations:
- This project was built with Unity 2022.3 LTS using the Universal Render Pipeline (URP) and XR Interaction Toolkit (3.2.1).  
- This project contains 3 scenes, the correct one to run is the MainScene (Not BasicScene, Not SampleScene).
- All the required packages are already included in the project.
  
  
Optional Part:
- Baked light inserted
- Spatial 3D audio
- Height Map on the main material used for all the tables
- Visual Feedback for interaction (only the cube)
- Shader applied to the material of the cube on the left side. 

NOT PRESENT: shader -> I had problems in setting up a Shader Graph wich I was not able to solve


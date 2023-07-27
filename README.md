Survival Horror
===============
Version: Early Pre Alpha, Unreal Engine 4.27.2
===============
Game Purpose:
===============
Fulfillment of the goals set for the player by completing tasks (moving the player through the level to the end point), solving puzzles, exploring the environment, searching for the right items.

Currently Implemented:
===============
Custom Character Movement System (Char Speed, Camera Shake based on direction and current action);

Interactive and focus character system, focus (trace) for interaction is enabled based on interactive objects around the character (subject to availability);

Inventory / containers system, the ability to preview items and make decisions, take, leave, put out of the container (items appear on screen and await action one by one).

Parent class for Interactable objects, configurations such as displayable buttons (could be set for hint),  permanent use(busy char), highlighting the item (stencil), displaying the focus point, messages.

Inspectable objects (derived class from Interactable objects), objects on which the character can focus, read their description, depending on the preset, it is possible to take actions such as pick up, throw, put back.

Main menu, custom sub-objects, support for mouse and gamepad.

Plans:
===============
At the moment, the project is at the Early Pre Alpha stage. Now I am rewriting the project in C++ and moving it from UE 4.27.2 to UE 5.2.1, in the new version I plan to improve and refine the mechanics, as well as add new ones.
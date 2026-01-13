[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## Devlog

1. Jasmine Caicedo, They/ She/ He (any/ all pronouns are fine, I don't care which are used when refering to me)


2. Basically everything was able to connect to what me and my team wrote up for our plan. Our groups plan wasn't step by step, so some things are a bit out of order, however, it can be sumarized. In general, we first decided to focus on the player, and we planned for the class to have member variables that would interact witin the script itself, and also involve calling meathods from the UI meathod. Specifically, we first worked on getting the movement (which we stated in our breakdown as an action that needed to be completed in the update funtion), this was done by using the member variable of the players transform values and manipulationg them. This lets the player in the scene move arond with both WASD and the arrow keys. The only thing different that I added that we didnt reference in the breakdown is the multiplication of the directions with time.deltatime and the speed (which is also a member variable) so that the player moves smoother. The next thing we did as we wrote in the breakdown that I emulated in the code is the instantiation of a prefab (created as an instance into a gameobject by a member variable called _plantPrefab) within the meathod PlantSeed, this would alow (as also stated in the breakdown) that in the update function every time the player presses space, a plant shall be placed or spawned into the scene. These conditions in the if statement (to cause a plant to be placed other than just pressing space) include the use of a different class called "PlantCountUI" in order to log the ammounts of plants placed. The public meathod of "UpdateSeed" was used in order to do this. This other condition for the if staement wasn't directly mentioned in the breakdown. The logic was the same in the breakdown my group did, but was much more fleshed out here. 


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites

# GDIM 33 In-Class Activities
## W1
### Activity 1
1. I wana build a vertical slice about Roguelike 2D platform game. the game mechanism I get inspire from skul, Neon Abyss
I the art and world building I try to use some horror element, like bloodborne

[inspiration board](https://docs.google.com/drawings/d/1TRcu9-EYq8SjLIblz96NiOaWDUoQ5sWvDAELnRJ0wdo/edit)

2. we have some topic about roguelike game 
3. our TA more like Rgp game. And I got some Idea about cut off some mechansim because it is ten week class it is not neccsary to final whole vertical slide


### Activity 2
[week1 break down](https://github.com/user-attachments/assets/d49d735b-6eb2-4d81-9507-2f526ba0bd29)


## W3
### Activity 1
break-down chart
<img width="1527" height="1080" alt="65BC933F-13D9-4933-AECB-73CA1ECD9D63" src="https://github.com/user-attachments/assets/b9381093-ebe3-4b99-b807-7355d26edf65" />


### Activity 2
1. same this variable as a scene varible which means I can use this varible in other visual script graph. I don't need create a new variable for trigger customer event
2. I use two Debug log node in both dialogue and explore state in state machine whihc help me to check work state change code is work before the whole code is finish
3. I think yes in my game there are two state first is in the game which have to use the Cursor lock and when player talking to NPC to update weapon. I need cursor to select
4. yes, Like I said in the pre- learning quiz I try to use state machine in change the state of enmey.

## W4
### Activity 1
Playtest Team memeber: Gong Chen, Alvin Wang, Ziyue Yang

Right I complete the shooting feature in my playtest build. Therefore in this play test, I want to test if the shooting feature is smooth for player

The result I think I need to add the phyiscal material to the ground and bullet to make bullet can be bound. And I think playtester every enjoy and make fun from my demo, this demo is so goofy but I want to make my game seriously.

### Activity 2

1. yes, in this project logic I create a chain of dialogue. which means writer can write new dialogue in the Scriptobject. and DialogueAdvance4W script and Node can can dislay next ScriptObject in the canvas
2. if the relpy is to large, in the visual scripting, creater have to build many node and make line for each not which means the coding will become difficulty
3. this button can let the C# to create a new node for the script object and after click the button this new node will add to the Visual script graph

## W5
### Activity 1
I will choice to use animator in my vertical slice

Big Step 1:

I will input all player and enemy animation and put them into animation Control. And change different animation by use trigger and bool.

Step 1: put sprite sheet into Asset File and build new file called Animation
Step 2: cut sprite sheet into each frame and add animator componet into player and enemy gameObject
Step 3: build Aninmation Control for enemy and player and set animation variable. 
Step 4: rotate the animation when the vector of transfrom change 

Big Step 2:

I will try to make the animation more smooth. including, don't let animation before the animation finish play even the state change. and let the attack check box enable when the play some frame play

Step 1: write the animation event script let animator play in a certain frame to sent event 
Step 2: write code in different scripts to respond the event
Step 0: watch video to how to write animation event 

### Activity 2
right now I finish the most part of Big Step 1 but the sprite sheet is the one I used before which is not match the whole Aesthetics in my game so I will try to update new sprite sheet in future. Also right now I work one rotate the sprite when player and enemy change direction.


## W6
### Activity 1
right now I update more enemy and they can change the state from wander, attack and follow. and more attack way

[playtest itch link same as milestone ](https://ruichenmamartin.itch.io/gdim-33-milestone-2)

I want player can understand the enemy state change and the rule of enemy move.

but I think the reason the map is too small and there no UI in the game so player understand enemy and the enemy Hp is also too small


### Activity 2

1. the RGB is float variable if mutiply third float the result will become small

2. Alpha is also a float and smaller than I

3. base on th shiba UV value

4. in the photograph and aftereffect can use RGB to change the color

## W7
### Activity 
1. coming from Geometry category, maybe come from the mesh date from the object

2. because they’re interpolated across the adjacent vertices that make up the polygon that this fragment is a part of.

3.  because they didn't not have 2d texture and alpha in the fragment. it only grab the color from the mesh date of this object. it wil make the object become colorful when the texture don't work. 

4. the normal of the shiba object is opposite

5. maybe it can debug UV of object

6. the vector on the shiba model is opposite to the vector of light which make the dot production result become negative

7. they use R G to cauluate and time with therefore the material will change like aninemate 

## W8 
### Activity 1
(itch link for playtest)[https://ruichenmamartin.itch.io/milestone-3]

add a NPC who can help player update it weapon

for this playtest I want to test the bug of animation of enemy which is I build in milestone 2. I have a playtest before the milestone 2 but I want make more test to make sure there are no bug. Also I want to make sure the player can understand who is npc and what npc can do. even I do not say anything.

Playtest result. First my animation don't have bug but I think I can make the hit box become invisiable. But some player do not what NPC can do before I tell them.one more thing is that the weapon level don't have limit.

### Activity 2



In Step (4), why does changing the Layer the Shiba is on enable and disable the outline effect? If you’re not sure, look back on Step (4).

2A:shiba outline shader

1. create two render object feature which give value for the Stencil buffer and add material which is color of the outline and another let the shiba object can pass the outline color.

2. the DrawOpaqueObject and the StencilWeitePass both draw shiba which is because I create a new Stencil buffer let it pass the outline buffer

3. because one is work on the light side one is work one dark side is it mutiply it will not work but it add it will work

4. I think it is because the outline effect will work when the shiba one the outline layer during setting the rending object feature. if change layer it will not work.

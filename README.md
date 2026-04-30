# GDIM 33 In-Class Activities
## W1
### Activity 1
[Activity 1: brainstorm](https://docs.google.com/drawings/d/1ugxKbuKLlBbpqZvrLtJKdx3I6zAFIf1qCySLS28vePc/edit)
1. A clear pattern in my inspiration is my interest in inequality, oppression, and the lives of ordinary people under powerful systems. I want to combine a post-cyberpunk world with the class suffering and emotional intensity of Les Misérables, mixing advanced technology with poverty, control, and resistance. In terms of gameplay, I am most interested in fight and exploration
2. My classmate wants to make a cyberpunk survival horror game with a big story. Our styles are similar because we both like  strong atmosphere in game world. her game is more about horror, while mine is more about depict social pressure and unfair systems.
3. One LA said they are interested in making a multiplayer PvP shooting game. Our ideas are similar because both of us are interested in shooting elements. his game focuses more on competition between players, while mine uses shooting more as part of the world, conflict, and story.



### Activity 2
[Activity 2: break-down](https://docs.google.com/drawings/d/1NqhMj7zMddQUyuUmfBft3l2naNNAFNeYzsN6Gl916Xo/edit?usp=sharing)


## W3
Activity 1，[Break-down](https://docs.google.com/drawings/d/1NqhMj7zMddQUyuUmfBft3l2naNNAFNeYzsN6Gl916Xo/edit?usp=sharing)

Activity 2，

  1, It is because the same event name can be reused in different Graphs. If you want to change name, it only need to change it in one place. 
  
  2, Debug.Log() helped me check if one of the event in the graph was being triggered correctly in the whole system.
  
  3, Yes, My game has both normal movement and UI interface such as mission failing page, or pause page or inventory page, so locking and unlocking the cursor can help control when the player moves and when they use UI or inventory.
  
  4, Yes, in my game, the guards would have at least two states: a patrol state and an alert state. In the patrol state, the guard moves around in the area. In the alert state, the guard chases the player or attacks and shoots at the player.

## W4
Activity 1

I complete the move function of the player, use WASD and mouse to control the charactor.

Goal：testing if a movement of player feels smooth 

  1. the animation is not finished, and sometimes the character still appears to move even when no keys are being pressed （Yan Zhang）
     
  2. the movement speed feels too slow, so I need to adjust it to make the controls feel better. （JingyiBi）
     
  3. when the player stops pressing WASD, the character snaps back to a default direction. （Tina Meng，Xichan Zheng）


Acticity2,

1，Yes, a writer could add more dialogue without writing code. After the system is set up, they can just create more dialogue node, write lines and add reply options in the Inspector. The code and graph already handle the logic.

2, The writer can create as many dialogue layers. The limit is the UI, because the screen can only fit about 4 reply options.

3, The Regenerate Nodes button updates the Visual Scripting node library so Unity can recognize new C# code, methods, and events as nodes.

## W5
activity1:

Step 1: Build the basic weapon switching system
  1,Create two player states in the Visual Scripting State Machine: Unarmed and PistolEquipped.
  Add the pistol GameObject to the player and connect it to the state system.
  In the Unarmed state, keep the pistol hidden.
  In the PistolEquipped state, make the pistol visible.
  Add transitions between Unarmed and PistolEquipped using the Tab input.
Step 2: Add aiming behavior inside the pistol-equipped state
  Use the right mouse button input to detect when the player is aiming.
  Connect the aiming input to the Animator through the parameter.isAiming
  While aiming, lock the player’s movement input but keep camera movement active.
  When the right mouse button is released, return the player to the normal pistol-equipped pose.
  Make sure the player can still switch back to the Unarmed state with Tab.
Step 3: Polish the draw-gun flow and animation logic
  Clean up the transitions so the switch between unarmed, equipped, and aiming feels smooth.
  Adjust the pistol position so it looks correct in the player’s hand.
  Make sure the player must equip the gun first before aiming.
  Figure out whether I need a separate short “draw gun” animation between Unarmed and PistolEquipped, or if switching directly is enough. Ask in class or office hours if needed.
  Finalize the full gameplay loop: unarmed → equip pistol → aim → lower weapon → unequip pistol.

 activity 2
  

  

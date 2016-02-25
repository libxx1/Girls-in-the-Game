---
title: Get into the Game
level: Scratch 1
language: en-GB
stylesheet: scratch
embeds: "*.png"
materials: ["Club Leader Resources/*"]
...

# Introduction { .intro }

You are going to learn how to program your own animation!

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="http://scratch.mit.edu/projects/embed/95843402/?autostart=false" frameborder="0"></iframe>
  <img src="football-final.png">
</div>

# Step 1: Sprites { .activity .new-page}

Before you can start coding, you’ll need to add in a ‘thing’ to code. In Scratch, these ‘things’ are called __sprites__.

## Activity Checklist { .check }

+ First, open up the Scratch editor. You can find the online Scratch editor at <a href="http://jumpto.cc/scratch-new">jumpto.cc/scratch-new</a>. It looks like this:

	![screenshot](football-editor.png)

+ The cat sprite that you can see is the Scratch mascot. Let’s get rid of it, by right-clicking and then clicking ‘delete’.

	![screenshot](football-felix.png)

+ Next, locate the ‘New sprite’ icons. Click ‘Choose sprite from library’ to open up a list of all the Scratch sprites.

	![screenshot](football-library.png)

+ Search until you see a sprite called ‘Adrian’. Click on her and click the ‘OK’ button from the bottom-right corner to add her to your project.

	![screenshot](football-adrian.png)

## Challenge: Adding another sprite {.challenge}
Can you add the sprite ‘Soccer Ball’ to your project?

## Activity Checklist { .check }

You’ll notice the soccer ball is too big. You can resize sprites by clicking on the ‘shrink’ icon, located in the top toolbar, then clicking on the sprite you want to change. 

	![screenshot](football-shrink.png)

## Save your project { .save }

You can give your program a name, by typing over ‘Untitled’ in the top-left corner text box.

If you are signed in to an account you can then click ‘File’ and then ‘Save now’ to save your project. If you don’t yet have an account but wish to save your program you can ‘Join Scratch’ via the drop down arrow in the top-right corner (you will not lose your progress by clicking this option).

![screenshot](football-save.png)

# Step 2: The Stage { .activity .new-page }

The stage is the area on the left, and is where your project comes to life. Think of it as a performance area, just like a real stage! 

## Activity Checklist { .check }

+ At the moment, the stage is white, and looks pretty boring! Let’s add a backdrop to the stage, by clicking ‘Choose backdrop from library’.

	![screenshot](football-backdrop.png)

+ Click ‘Outdoors’ on the left and then click on a goal backdrop and click ‘OK’.

	![screenshot](football-goal.png)

	Your stage should now look like this:

	![screenshot](football-stage.png)

# Step 3: Animating your footballer { .activity .new-page }

Let’s code Adrian to kick the soccer ball sprite. 

## Activity Checklist { .check }

+ To make Adrian look like she is kicking the ball we need two of her costumes. From the ‘Sprites’ box, click on the icon for Adrian, then on her ‘Costumes’ tab, and you’ll see 3 costumes.

	![screenshot](football-costumes.png)

+ The names of the costumes aren’t very helpful at the moment. Rename ‘adrian-a’ to ‘kicking’ and ‘adrian-b’ to ‘standing’ by typing the new name of each costume into the text box. 

	![screenshot](football-rename.png)

+ Now we need to add some code. You can find the code blocks in the ‘Scripts’ tab, and they are all colour-coded! Drag these blocks into the code area to the right, making sure that they are connected together (like Lego blocks):

	![screenshot](football-kick.png)

## Save your project { .save }

# Step 4: Moving the ball { .activity .new-page }

When Adrian has kicked, you need to `broadcast` {.blockevents} a message to the soccer ball sprite, telling it to move.

## Activity Checklist { .check }

+ To do this, first add this block to the end of your code.

	![screenshot](football-broadcast.png)

To create the `broadcast` {.blockevents} block, click the down arrow and select ‘new message…’.
You can then type ‘kick’ to create your new message.

	![screenshot](football-extend.png)

+ You now need to tell your soccer ball sprite where to start and what to do when it receives the message. Click on your soccer ball sprite icon and add this code. 

	![screenshot](football-move.png)

The `repeat` {.blockcontrol} block is used to repeat something lots of times, and is also known as a __loop__. 

+ Click on the green flag, next to where you named your project, to see your new animation in action. 

# Step 5: Some fans { .activity .new-page }

Now we’re going to add some fans to cheer when Adrian kicks the ball into the net. 

## Activity Checklist { .check }

+ Let’s add a new sprite called ‘Anna’ from the library. Anna has 2 costumes, we’ll use them both to make it look like she’s cheering when a goal is scored.

	![screenshot](football-anna.png)

## Challenge: Preparing to animate {.challenge}
Can you rename Anna’s costumes to arms-side and arms-up to make them more obvious?
If Anna is a bit too big, can you use the shrink tool to resize her. 

## Activity Checklist { .check }

+ To make sure Anna cheers at the right time, we need to add an extra block onto the end of our soccer ball script to `broadcast` {.blockevents} a message when a goal is scored. You’ll need to create a new message and call it something that is easy to remember.

	![screenshot](football-start.png)

+ Next, click on Anna and add these code blocks.

	![screenshot](football-cheer.png)

+ Click on the flag to see your new animation.  

## Save your project { .save }

## Challenge: Expanding your animation {.challenge}
Can you personalise the footballer? Perhaps change her hair colour or kit.

Can you add some more fans to your project?

Can you make the fans say encouraging words?

Can you add some sounds to your project?

## Save your project { .save }

#Angry Birds

* Based on Chapter 2 (Making your own Angry Birds Game) from ‘[Raspberry Pi Projects for Kids](http://www.amazon.com/Raspberry-Projects-Kids-Daniel-Bates/dp/1783982225)’ (PACKT Publishing) by Daniel Bates
* [Scratch help and tutorials](https://scratch.mit.edu/help/) 

###Instructor Notes
* Encourage students to follow their curiosity and depart from lesson plan (keeping within time limits so everyone moves ahead together).
* Answer questions by asking students to try it and see (not just show & tell).
* There will be a short class-wide demo before the start of each section to explain what is expected. 
* The Chapter is for instructors only; share the objectives with the students but not the answers in the chapter.

![Sample](https://raw.githubusercontent.com/gritcoding/twf/master/images/angrybirds_sample.jpg)

[Sample](http://scratch.mit.edu/projects/37783950/) (thanks Moon):  

###Introduction (10 mins)
* Walkthrough the interface and the basic code blocks.

###Hello World (10 mins)

##### Objectives
* Make a sprite move, rotate
* Bonus: change costumes, add sound

##### Demo
![Hello World](https://raw.githubusercontent.com/gritcoding/twf/master/images/angrybirds_helloworld.jpg)

* Show motion variables: x, y, direction.
* Right-click for help.

##### Ideas
* How many degrees in a circle?
* Can you point your sprite Up, Down, Left, Right?

![Faiz](https://raw.githubusercontent.com/gritcoding/twf/master/images/angrybirds_faiz.jpg)

###Creating a character, Creating a level (20 mins)

##### Objectives
* Create a stage with background, ground, and Slingshot
* Add a sprite
* Bonus: Add costumes to sprite, scenery, objects

##### Demo
![Hello World](https://raw.githubusercontent.com/gritcoding/twf/master/images/angrybirds_level.jpg)
* solutions/angrybirds/01_level.sb

##### Ideas
* How large is my stage, in pixels? Where is x=0, y=0?
* How can I tell the x, y where my mouse is pointing?
* Did you name your sprites?
* Zoom out in editor to see the entire canvas.
* Don’t forget to save!

###Moving with the keyboard, Launch, Flight, Physics (40 mins)

##### Demo
![Hello World](https://raw.githubusercontent.com/gritcoding/twf/master/images/angrybirds_launch_demo01.jpg)
![Hello World](https://raw.githubusercontent.com/gritcoding/twf/master/images/angrybirds_launch_demo02.jpg)
* solutions/angrybirds/02_launch_flight.sb

* Move bird to slingshot.
* Press spacebar to launch bird (broadcast and receive).
* Change x and y by fixed amounts. Show how changing the values of x and y affects flight path.
* Introduce (sprite) variables; let students figure out how much to change the variable.
* Gravity.
* [Explanation of Flight and Speed code for Angry Birds](ANGRY_BIRDS_SPEED_CODE.md)

##### Objectives
* Move and launch bird from slingshot.
* Add variables.
* Stop when bird hits ground, edges of screen (or other objects). Or bounce around.
* Bonus: animation, sound, gravity, bounce on ground before coming to stop.

##### Ideas
* Where is the sprite center (costume edit)?
* What is the difference between 'move by' and 'change x by'?
* Right-click on scripts to duplicate.
* How can I make my sprite move faster? Slower?
* The flight code is complex; first move by fixed x,y and then build the formula by introducing variables. Don’t get stuck on the formula but make sure to understand how assignment of ‘x speed’ and ‘y speed’ works.


###Scoring, Extensions (40 mins)

##### Demo
![Hello World](https://raw.githubusercontent.com/gritcoding/twf/master/images/angrybirds_scoring.jpg)
* solutions/angrybirds/03_scoring.sb

##### Objectives
* Add monster(s).
* Add scoring.
* Reset bird and monsters on start.
* Bonus: Different kinds of monsters and scores, multiple birds, animations (e,g, hop on slingshot, flight), sounds, power-ups (e.g. press a key to speedup).

##### Ideas
* Score is a global (all sprites) variable.
* Duplicate your monster (and birds) when you're done with the first one.
* How can you make each bird independant (birds can hop on slingshot in sequence, or use key presses or mouseclicks)? And each monster react to each bird?

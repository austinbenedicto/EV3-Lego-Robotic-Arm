# EV3-Lego-Robotic-Arm

We have done a lot of work on getting the robot arm working. We have gotten to the place where we understand almost everything that was previously done.

The two ev3 brains connect to each other through wifi connection as the code is written right now. 
The brains can be connected through a USB to mirco USB cable.
The PS4 controller conects through bluetooth to the one of the ev3 brains.
One of the brains acts as a main controller and the other acts like motor slave to the other brain.
It doesn't matter which brain is the slave and which one is the main controller.
To asign main controller you need to connect both hubs to one wifi network, then pick which one is the slave and find its IP address and change an array in robot-arm.py to the IP address.

We still need to make a button map of what everything does
We are still trying to figure out how to connect the controller
We are also trying to figure out connection errors and why the we are constally lossing connection with the the ev3 brain

We want to figure out how to make everything work the way it was orrgoinally programmed and designed. With the brains connecting through wifi before we change over to a wired connection.
The code also has to be fully commited which will get done as soon as we understand most of the code and what it does.
There is also code written for useing sensors and I think that it would be fun to have that working as well. I think that it would be cool if that was added once everything above was accomplished.

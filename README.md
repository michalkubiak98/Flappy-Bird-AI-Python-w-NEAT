# Flappy Bird AI Python with NEAT

## I have been wanting to complete this project for a while, so this weekend i finally got it done.

I satrted off with Pip3 installing pygame, neat-python. Created sub folders and the .py file.

I followed along with the tutorial, figuring out which things need to be objects and which methods. Pipes, Bird and Base were all objects.

I made those 3 classes, with their internal methods.

Defined images, defined class bird and self, jump, move, methods.

Drew window, made a main class which makes a bird object and while True drew the window with the bird object animated with 3 imgs. This allowed the bird to be animated between the 3 images, making it appear to be flying.



Made pipe class, defined top and bottom pipes and their co-ords and movement by velocity so it moves to the left.

Using a mask and the images having transparent bg’s, it will figure out pixel perfect walls for collision. It creates a 2d array of lists and fills with pixel values and it will compare the two boxes to see if we have pixel perfcet collision with pygame function mask



Make base move with 2 base displacing one after another moving left.

Main keep score and remove pipes after theyre off the window

Moved onto NEAT config. Started by creating lists holding the genome itself, the neural network associated with the genome and the bird object that uses that network to play

Sent bird location, top pipe location and bottom pipe location and determine from network whether to jump or not

Run up to 50 generations



2 birds are left upon starting after initial 95% die in the first few pipes

For efficiency in larger projects this would set the time from 30 fps to as fast as possible


This was a great project and i had a lot of fun with it, The author is Tech with Tim on youtube at https://www.youtube.com/watch?v=MMxFDaIOHsE&ab_channel=TechWithTim


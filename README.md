# PacManProject
MIT xPRO Full Stack Development Bootcamp Assignment

This program relies on 4 images: right facing open mouth, right facing closed mouth, left facing open mouth, left facing closed mouth. 

Three functions are used: Run() which move the images from side to side along the x-axis, changes the images between open and closed mouths, 
and checks to see if the left position of the image has reached the screen's edges.  checkPageBounds() is used to actualy see if the images has reached the screen's edge, 
change the direction the image moves (left or right), and also affects the images that are used (left-facing or right-facing).  setInterval() calls the Run() function every
200 miliseconds.

Download all of the files into one folder, then drag the index.html file from your file explorer into your browser to watch PacMan scroll across your screen.

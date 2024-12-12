# a121_catch_a_turtle.py

#-----Location to import all the modules that you will use to make the Catch-A-Turtle game.-----
import turtle

#-----Where all the variables will be defined and initialized.----
spot_color = "pink"
spot_shape = "circle"
shape_size = 2

#-----Where all the turtles for your game will be created. This is also where you will change any configurations to those turtles such as start position, color, and size.-----
spot = turtle.Turtle()
spot.shape(spot_shape)
spot.shapesize(shape_size)
spot.fillcolor(spot_color)

#-----Where you will have all of your function definitions.--------

#-----Events is where you will have the event listeners. Listeners work in the background of a program and are used to “listen” for an event such as a key press.----------------

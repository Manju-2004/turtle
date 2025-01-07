import turtle
shape=turtle.Turtle()
colors=["purple","red","blue","light blue"]

for color in colors:
    shape.fillcolor(color)
    shape.begin_fill()
    for i in range(4):
        shape.forward(100)
        shape.right(90)
    shape.end_fill()
    shape.penup()
    shape.forward(120)
    shape.pendown()
turtle.done()

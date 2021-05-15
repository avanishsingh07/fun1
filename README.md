# fun1
keep_eye_on_Me with hearth

import turtle
pen = turtle.Turtle()
def curve():
    for i in range(200):
        pen.right(1)
        pen.forward(1)
def heart():
    pen.fillcolor('orange')
    pen.begin_fill()
    pen.left(140)
    pen.forward(113)
    curve()
    pen.left(120)
    curve()
    pen.forward(112)
    pen.end_fill()

def txt():
    pen.up()
    pen.setpos(-68, 95)
    pen.down()
    pen.color('magenta')
    pen.write("#keep eye on ME ", font=(
      "Verdana", 12, "bold"))
heart()
  
txt()
  
pen.ht()

# bunga.py
import turtle
tu = turtle.Turtle()
tu.screen.bgcolor('black')
tu.pensize(2)
tu.left(100)

tu.backward(100)
tu.speed(3000)
tu.shape("turtle")

def bunga (i):
	if i <10:
		return
	else:
		tu.forward(i)
		tu.color("white",)
		tu.circle(2)
		tu.color("green")
		tu.left(30)
		bunga(3*i/4)
		tu.right(90)
		bunga(3*i/4)
		tu.left(60)
		tu.backward(i)
bunga(120)
turtle.done()
#inidel

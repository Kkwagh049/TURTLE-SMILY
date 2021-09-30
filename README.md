# TURTLE-SMILY
python turtle Graphics smile code
import turtle as t1 #Smily emoji using turtle
t1.getscreen()
t1.bgcolor("blue")#set background
t1.fillcolor('yellow')#start filling color to circle
t1.pencolor("red")
t1.pensize(2)
t1.begin_fill()
t1.circle(150)
t1.end_fill()
t1.up()
# Draw eyes 
t1.penup()
t1.goto(-40,120)
t1.pendown()
t1.pencolor("black")
t1.fillcolor("white")
t1.begin_fill()
t1.circle(20)
t1.end_fill()
t1.lt(90)
t1.penup()
t1.fd(20)
t1.pendown()

# draw pupil
t1.fillcolor('black')
t1.begin_fill()
t1.circle(5)
t1.end_fill()
t1.rt(90)
t1.penup()
t1.goto(40,120)
t1.pendown()

# draw eye left
t1.fillcolor("white")
t1.begin_fill()
t1.circle(20)
t1.end_fill()
t1.lt(90)
t1.penup()
t1.fd(20)
t1.pendown()

# Draw pupil left
t1.fillcolor("black")
t1.begin_fill()
t1.circle(5)
t1.end_fill()
t1.penup()
t1.goto(0,0)
t1.pendown()
t1.penup()
t1.fd(55)
t1.pendown()

# Create Smily
t1.lt(60)
t1.fd(100)
t1.bk(100)
t1.rt(120)
t1.fd(100)
t1.ht()
t1.done()



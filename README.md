# py_misson

import turtle
import time
turtle.speed(0)


def idx (gugudan):
    for i in range(1,10):
        print(gugudan,"x",i,"=",gugudan*i)

x=int(input("구구단 몇단을 입력할까요?"))
idx(x)

def ogakhung():
    for i in range (6):
        turtle.begin_fill()
        turtle.forward(20)
        turtle.left(60)
        turtle.fillcolor("black")
        turtle.end_fill()


ogakhung()
turtle.left(240)
ogakhung()
for i in range (4): 
    turtle.forward(20)
    turtle.right(60)
    ogakhung()

turtle.right(37)
for i in range(5):
    turtle.forward(35)
    turtle.right(144)
time.sleep(3)

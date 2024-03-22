# zirniyahahha
x1 = 5
def setup():
    size(800,600)
    
def draw():
    global x1
    strokeWeight(x1)
    point(350,200)
    point(380,230)
    line(350,200,380,230)
    point(350,260)
    line(350,260,380,230)
    point(320,230)
    line(350,200,320,230)
    line(320,230,350,260)
    x1 = x1 + 1

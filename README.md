# return
def MyApp(x,y):
    return x+y
def MyPower(x,y):
    a=x**y
    return MyApp(x,a)
result=MyPower(10,4)
print(result)

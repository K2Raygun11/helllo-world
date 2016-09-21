# helllo-world
Python

def repeater(s1,s2,n):
    print('_'+(n*(s1+s2))+'_')
    return;

def roots(a, b, c):
    x1= ((-b + (b**2-4*a*c)**(0.5))/(2*a))
    x2= ((-b - (b**2-4*a*c)**(0.5))/(2*a))
    return 'The quadratic equation with coefficients a = ' + str(a) + ', b = ' + str(b) + ', c = ' + str(c) + ' has the following soloutions '+ str(x1) + ' and '+ str(x2)

def real_roots(a,b,c):
    if b**2-4*a*c>=0:
        print("True")
    else:
        print("False")

def reverse(x):
    f=x//10
    s=(x-(f*10))*10
    print(f+s)
    return;

# a udda
def romb(a,b):
    i=(a+1)//2
    for j in range(i-1):
        print((b+i-j-1)*' ' + (1+(2*j))*"*")
    for j in range(i):
        print((j+b)*' ' + (a-(2*j))*"*")
# a udda
def triupp(a,b):
    i=(a+1)//2
    for j in range(i):
        print((j+b)*' ' + (a-(2*j))*"*")
# a udda
def triner(a,b):
    i=(a+1)//2
    for j in range(i):
        print((b+i-j-1)*' ' + (1+(2*j))*"*")
# b avstånd, n höjd, m längd, a tecken
def rekt(b,n,m,a):
    for j in range(n):
        print(b*" " + m*a)
# minsta a eller b, dividera med 2, avrunda upp, subtrahera 1, högsta c
# a = kolumner, b = rader, c = tjocklek
def ram(a,b,c):
    for j in range(c):
        print(a*'*')
    for j in range(b-2*c):
        print(c*'*' + (a-2*c)*' ' + c*'*')
    for j in range(c):
        print(a*'*')

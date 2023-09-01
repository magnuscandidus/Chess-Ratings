# Chess-Ratings
# cook your dish here
for i in range (int(input())):
    x,y = map(int,input().split())
    if(x==y):
        print("0")
    elif((y-x)%8==0):
        print((y-x)//8)
    else:
        print((y-x)//8 + 1)

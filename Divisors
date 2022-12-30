intg = input("a b: ").split(" ")
list= []
ab = False
for i in intg:
    list.append(int(i))
while ab== False:
    if int(intg[0])>0 and int(intg[0])<int(intg[1]) and int(intg[1])>0:
        ab= True
    else:
        list.clear()
        intg = input("a b: ").split(" ")
        for i in intg:
            list.append(int(i))


divisor = input("Divisors: ").split(" ")
nlist = []
Div= False
for c in divisor:
    nlist.append(int(c))
while Div== False:
    for t in nlist:
        if t>0 and t<= list[1]:
            Div= True
        else:
            nlist.clear()
            Div= False
            divisor = input("Divisors: ").split(" ")
            for c in divisor:
                nlist.append(int(c))
nlist.sort()
#for nlist to be in ascending order

print("M", end=" ")
gap= 1
for d in nlist:
    if gap < len(nlist):
        print(d, end=" ")
        gap += 1
    else:
        print(d, end="")
        print( )
for i in range(int(list[0]),int(list[1])):
    gap= 1
    print(i, end=" ")
    for d in nlist:
        if i%d== 0:
            if gap< len(nlist):
                print(1, end=" ")
                gap +=1
            else:
                print(1, end="")
                print( )
        else:
            if gap< len(nlist):
                print(0, end=" ")
                gap +=1
            else:
                print(0, end= "")
                print()

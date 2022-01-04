# Debug-a--python-program
import pdb-------->module

bike1='yamha'
bike2='tvs'
bike1_price=20000
bike2_price=10000
name=input("enter ur name:")
pdb.set_trace()-------------->command
print(f"hello {name}")
user=int(input('press 1 or press 2'))
if user==1:
    print(f"ur bike is {bike1}", end = ''  )
    print(f"its price is {bike1_price}")
elif user==2:
    print(f"ur bike is {bike2}",end = ' ')
    print(f"its price is {bike2_price}")

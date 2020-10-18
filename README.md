def logo():
 print("  ___                   _____       _            _       _              ")           
 print(" / _ \                 /  __ \     | |          | |     | |             ")           
 print("/ /_\ \_ __ ___  __ _  | /  \/ __ _| | ___ _   _| | __ _| |_ ___  _ __  ")
 print("|  _  | '__/ _ \/ _` | | |    / _` | |/ __| | | | |/ _` | __/ _ \| '__| ")
 print("| | | | | |  __/ (_| | | \__/\ (_| | | (__| |_| | | (_| | || (_) | |    ")
 print("\_| |_/_|  \___|\__,_|  \____/\__,_|_|\___|\__,_|_|\__,_|\__\___/|_|    ")
                                                                        
                                                                        
                                                                                             
def AreaCalculator():
  shape = int(input("What shape do you want to calculate ?\nsquare is 1 \nrectangle is 2 \ncircle is 3 \ntriangle is 4 \nEnter choice:"))
  if shape == 1:
    return square()
  elif shape == 2:
    return rectangle()
  elif shape == 3:
    return circle()
  elif shape == 4:
    return triangle()
  else:
    print("Invalid number, please try again")


def square():
    side = int(input ("please enter the side lenght ") )
    area = (side * side)
    print(area)


def rectangle():
    base = int(input("please enter the base ") )
    length = int(input("please enter the lenght ") )
    area = (length * base)
    print(area)
 

def circle ():
    radius = int (input ("please enter the radius ") )
    area = 3.14 * radius * radius
    print (area)

    
def triangle ():
    base = int (input ("please enter the base " ) )
    heght = int (input ("please enter the heght " ) )
    area = base * heght /2
    print (area)

logo()
AreaCalculator(

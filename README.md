# Python-Treser-hunt
print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
direction=input('you are at the end of the road. '
                'Type "left" for left or "right" for right:').lower()
if direction == "left" :
    print("You come to a lake, There is an island in the middle of it.")
    lake_point=input("Type wait for waiting for a boat or"
                     " Type Swim for Swim across the lake: ").lower()
    if lake_point == "wait":
        print("You arrive at the island unharmed. "
              "There is house with three Colour.")
        door_colour = input("One red, one blue, one white. "
                            "Which colour do you choose? ").lower()
        if door_colour == "red" :
            print("Burned by fire Game over.")
        elif door_colour == "blue":
            print("Eaten by beast, Game over")
        elif door_colour == "white":
            print("you win!!!!")
        else:
            print("Game over.")
    else:
        print("Attacked by trout, Game over")
else:
    print("Fall into hole, Game Over")
    

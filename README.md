A wild west choose your own adventure game I created using Python!

print("Welcome to the Wild West boy.")
print("Your mission is to stay alive.")

first_choice = input('"This looks shady.", you say quietly to yourself as you come to a Saloon.\n Would you like to enter? "yes" or "no"\n').lower()
if first_choice == "yes":
    # Continue in the game.
    second_choice = input('"You see a tan dirty man with a low brim covering a cheek scar.\n Sit next to him? "yes" or "no"\n').lower()
    if second_choice == "yes":
        print("You're not from around here is ya? He muttered under his mangy stache. You're all the same,\n thinking everything ought to be handed to ya on a silver platter.")
        # Continue in the game.
        third_choice = input('Type "pardon" to stand up for yourself? Or type "ignore" to just let it go?\n').lower()
        if third_choice == "pardon":
            # Continue in the game.
            print('"You ask How did you get that scar?", running your mouth? Before your cheek muscles can even form a grin, he jumps up flipping his stool\n while slicing the air with a leatherman blade from nowhere reaching your jugular.')
            fourth_choice = input('Do you want today to be your last? He asks menacingly. \n type "yes" or "no"\n').lower()
            if fourth_choice == "yes":
                # Game Over.
                print("Sionara sucka! You DEAD.")
            else:
                print("That's not for you to decide! A gentlman's dual is in order.\n Meet me at high noon and I'll show you how I got that scar....To be continued.")
        else:
            # Game Over.
            print("You stare ahead counting the splinters in the wall as you finish your once chilled mug of Nuka Cola...")
            print("This can't be how the story ends? But it's already over.")
    else:
        print("You find a booth in the dimly lit corner, comfortably sit back, relax and enjoy yourself for once.\n I deserve this you think as you sip your Nuka Cola.")
else:
    # Game Over.
    print("You're too good for this town anyway you think,\n as you ride off on your trusty steed to wreak havoc on the next town.")

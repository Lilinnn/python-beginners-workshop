TASK 01
=======

If/Else
-------


A) Type the following code, save it in a file and try to understand what it does.
B) Run the file and check if what you imagined really happens.
C) Get creative! Right after the inline comments, add a second door using the elif statement.


::

    print()
    print("Welcome to the dungeon!")
    print("Do you go through door 1 or door 2?")

    door = input("> ")

    if door == "1":
        print("There is a nice vampire asking you if you enjoy life.")
        print("What do you do?")
        print("1. Smile and nod")
        print("2. Scream and run")

        vampire = input("> ")

        if vampire == "1":
            print("Congratulations, you found a new friend!")
        elif vampire == "2":
            print("Sorry, the vampire is faster. You become a dinner.")
        else:
            print("You are not so good with numbers, are you?")

    # Exercise C

    else:
        print("You are not so good with numbers, are you?")

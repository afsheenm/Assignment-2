print("Helloww Python!")



# define a function to test modulo operation
def modulo_testing():

# get dividend and divider from user input
    x = input("Give me a dividend: ")
    y = input("give me a divider: ")

# calculate the remainder and print it
    z = float (x) % float (y)

    print("The remainder is: " + str (z))

modulo_testing()

# define function  to test integer division
def integer_division_testing():

# get numbers to divide from user input
    x = input("Give me a number to divide: ")
    y = input("What do you want it divided by: ")

# calculate the result and print it
    z = float (x) / float(y)

    print("The result is: " + str(z))

integer_division_testing()


# define a function to count using a for loop
def for_loop_counter():

# loop 40 times and print the counter value
    for x in range (40):
        print("Counter value: ", x)

for_loop_counter()

# define function to perform basic arithmetic calculations
def float_and_integer_calculator():

# get two numbers from user input
    num1 = float (input("Enter first number: "))
    num2 = float (input("Enter second number: "))

#ask user to choose operation
    user_str =  int(input("Choose method of calculation: \n 0: Addition \n 1: Subtraction \n 2: Multiplication \n 3: Division\n"))

#perform the chosen operation and print result
    if user_str == 0:
        result = num1 + num2
        print("The result is: ", result)

    elif user_str == 1:
        result = num1 - num2
        print("The result is: ", result)

    elif user_str == 2:
        result = num1 * num2
        print("The result is: ", result)

    elif user_str == 3:
        result = num1 / num2
        print("The result is: ", result)


float_and_integer_calculator()


#define the function to print ASCII values of letters
def print_ascii_values_of_letters():

    #get ascii value of letter M and print it
    letter_m = 'M'
    ascii_value_m = ord(letter_m)

    print("The ASCII value of m is ", ascii_value_m)

# loop through letters A-Z, get their ascii values and print them
    for letter in 'ABCDEFGHIJKLMNOPQRSTUVWXYZ':
        ascii_value = ord(letter)

        print("The acsii value of ", letter, "is", ascii_value)

print_ascii_values_of_letters()


#define function to calculate change
def change_machine():
     amount = float(input("Enter the amount in dollars: "))

#convert dollars to cents and calculate the number of each coin needed 
     cents = int(amount * 100)

     quarters = cents // 25
     cents %= 25

     dimes = cents // 10
     cents %= 10

     nickels = cents // 5
     cents %= 5

     pennies = cents

#print the number of each coin needed
     print("Quarters:", quarters)
     print("Dimes:", dimes)
     print("Nickels:", nickels)
     print("Pennies:", pennies)

change_machine()


#define function to play with computer
def rock_paper_scissors():
    import random
    # define options for the game
    options = ("rock", "paper", "scissors")

    #set loop to run the game multiple times
    running = True

    while running:
     player = None
     computer = random.choice (options)
     

     while player not in options:
       player = (input("Enter a choice: rock, paper, scissors: "))

     print(f"Player: {player}")
     print(f"Computer: {computer}")

     if player == computer:
        print("It's a tie!")

     elif player == "rock" and computer == "scissors":
        print("You win!")

     elif player == "paper" and computer == "rock":
        print("You win!")

     elif player == "scissors" and computer == "paper":
        print("You win!")

     else:
        print("You lose!")

     if not input ("Play again?: (Y/N)").lower()== "y":
      running = False
      break
     

    print("Thanks for playing!")
    

rock_paper_scissors()

#define function with how many stairs high and wide
def mario_wins_level():
    height = int(input("How many stairs do you want Mario to climb?: "))
    width = height 

#loop for the height
    for i in range(height):
      for j in range(width):

         if j <= i:
            print("#", end= " ")

         else:
          print(" ", end= " ")
    print()
    
    #if number less than 0 inputted, say invalid
    if height <= 0:
       print("Invalid Input")

mario_wins_level()

user_input = int(input("Which function do you want to run? \n 0: Modulo Testing \n 1: Integer Division \n 2: For Loop counter\n 3: Float integer calculator\n 4: ASCII values of letters \n 5: Change Machine\n 6: Rock Paper Scissors\n 7: Mario Wins a level\n"))

if user_input == 0:
    modulo_testing()
    
elif user_input == 1:
    integer_division_testing()

elif user_input == 2:
    for_loop_counter()

elif user_input == 3:
    float_and_integer_calculator()


elif user_input == 4:
    print_ascii_values_of_letters()

elif user_input == 5:
    change_machine()

elif user_input == 6:
    rock_paper_scissors()

elif user_input == 7:
    mario_wins_level()

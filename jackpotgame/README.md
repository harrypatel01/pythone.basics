# pythone.basics
-- jackport game while loop
jackpot = random.randint(1,100) 
guess = int(input("guess a number"))
counter = 1
while guess != jackpot:
    if guess < jackpot:
        print("guess higher")
    else:
        print ("guess lower")
    guess = int(input("guess a number")) 
    counter += 1
print("you win it")
print("you took", counter,"attempt")
 --- for loop
 

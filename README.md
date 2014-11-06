movies-program
==============
def movies():
    theater=True
    while(theater):
        total=0
        weather=input("Is it raining? ")
        if (weather=="yes"):
            theater=False
        amtPpl=eval(input("How many people are paying right now? "))
        for i in range(amtPpl):
            price=5
            age=eval(input("How old are you?"))
            if(age<12):
                price=price*0
            elif(age<60):
                price==12
            else:
                price=price

            id=input("Are you a veteran, nurse, student, or someone else ")
            if(id=="veteran"):
                price=price*0.6
            elif(id=="student"):
                price=price*0.7
            elif(id=="nurse"):
                price = price*0.65
            else:
                price=price

            total= total+price
            print(total)
            
            ##I did not know how to stop from looping through over and over again

import random


def relship():
    a=input("\nEnter your name:")
    b=input("Enter his/her name:")
    borr = ["friend","bestie","hater","Lover","Wellwisher","Traitor","Opposer","Enemy"]

    a1 =a.capitalize()
    b1 =b.capitalize()

    print(b1,"is",random.choice(borr),"to",a1)

    exit1()


def love_cal():
    points = 0
    print ("\nWelcome to the love calculator")
    Love1 = input("Please enter the first persons name\n")
    Love2 = input("Please enter the second persons name\n")
     
    L1 = (len(Love1))
    L2 = (len(Love2))
     
    S1 = (Love1[:1])
    S2 = (Love2[:1])
     
    if L1 == L2:
        points = points + 20
     
    if S1 == "a" or "e" or "i" or "o" or "u":
        points = points + 5
    else:
        points = points + 2.5

    if S2 == "a" or "e" or "i" or "o" or "u":
        points = points + 5
    else:
        points = points + 2.5
    print("So, the point is",points)
    
    exit1()

    

def single():
    global score
    score=0;

    print("Its -_- Rolling the dice -_- game")
    print("\nGetting 1,1 gains one point!")

    dice=[1,2,3,4,5,6]
    print ("\nRolling the dices...")
    print ("The values are....")

    d1=random.choice(dice)
    d2=random.choice(dice)
    print(d1)
    print(d2)

    while(d1==1 and d2==1):
        score+=1
    else:
        pass

    print("\nYour score is",score)
                    
                
    que=int(input("Do you want to roll the dice again? \n1.Yes\n2.No"))
    if(que==1):
           single()
    else:
           print("\nWe Singles are only Eligible for playing games...:) JFF :)")

           exit1()



def main1():
    print("What session do you need to get in..?")
    a=int(input("\n 1.Realtionship Finder \n 2.Love Calculator \n 3.Game for Singles"))
    if(a==1):
        relship()
    elif(a==2):
        love_cal()
    elif(a==3):
        single()
    else:
        print("\nwrong selection")

def exit1():
    c=int(input("\nDo you want to get into anyother session..? \n1.Yes \n2.No"))
    if(c==1):
        main1()
    else:
        print("\nThank you! Babbay.. :)")

print("<<<< Well,come!! >>>>")
main1()


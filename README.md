# The-Quiz-S--Rishab-Vivek
#this is a function so when I print the function this ASCII Art will print.
def title():
    print("""




 ▀█████████▄   ███    ███     ███    ███     ███    ███  ███    ███ ███  ██▀     ▄██     ███    ███ ███▀▀▀██▄     ███       ███    ███ ███
   ▀███▀▀██   ███    ███     ███    █▀      ███    ███  ███    ███ ███▌       ▄███▀     ███    ███ ███   ███     ███       ███    ███ ███
    ███   ▀  ▄███▄▄▄▄███▄▄  ▄███▄▄▄         ███    ███  ███    ███ ███▌  ▀█▀▄███▀▄▄     ███    ███ ███   ███     ███       ███    ███ ███
    ███     ▀▀███▀▀▀▀███▀  ▀▀███▀▀▀         ███    ███  ███    ███ ███▌   ▄███▀   ▀     ███    ███ ███   ███     ███       ███    ███ ███
    ███       ███    ███     ███    █▄      ███    ███  ███    ███ ███  ▄███▀           ███    ███ ███   ███     ███       ███    ███ ███
    ███       ███    ███     ███    ███     ███  ▀ ███  ███    ███ ███  ███▄     ▄█     ███    ███ ███   ███     ███▌    ▄ ███    ███ ███▌    ▄
   ▄████▀     ███    █▀      ██████████      ▀██████▀▄█ ████████▀  █▀    ▀████████▀      ▀██████▀   ▀█   █▀      █████▄▄██  ▀██████▀  █████▄▄██
                                                                                                                 ▀                    ▀




                """)

#this global will count the score

global vscore
vscore= 0

#this global will count how many restarts there are

global vtries
vtries=0

#this global will tell the total score at the end

global totalscore
totalscore=0

#this function will start from question 1 every time I print restart()

def restart():
     print(vquestion1())
#this function is my first question, globals at the start so when I use the variables later it will work
#and there will be no errors. Input so the user can input the answers. If statement if the answer is right
#it will add 1 point to score as well as move onto the next question. This is repeated for all 15 questions.
#Else statement if the answer is incorrect it will restart the game and add 1 try as well as starting the score
#from 0. repeated for all 15 questions

def vquestion1():
    global vscore
    global vtries
    vanswer=input("Which champ is known as 'The Blood Hunter'""\n"
                    "1. Vladimir" "\n"
                    "2. Teemo" "\n"
                    "3. Warwick" "\n"
                    "4. Rengar")
    if vanswer== "3":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion2()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()


def vquestion2():
    global vscore
    global vtries
    vanswer2=input("Question 2. Which champ has the passive 'Icathian Surprise'""\n"
                    "1.Wukong" "\n"
                    "2.Kog'Maw" "\n"
                    "3.Sion" "\n"
                    "4.Kindred")
    if vanswer2== "2":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion3()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion3():
    global vscore
    global vtries
    vanswer3=input("Question 3. How much damage does Yasuo's 'E' do at rank 3""\n"
                    "1. 70" "\n"
                    "2. 80" "\n"
                    "3. 100" "\n"
                    "4. 110")
    if vanswer3== "4":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion4()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion4():
    global vscore
    global vtries
    vanswer4=input("Question 4. What is Darius's 'W' called""\n"
                    "1. Hemorrhage" "\n"
                    "2. Noxian Guillotine" "\n"
                    "3. Decimate" "\n"
                    "4. Crippling Strike")
    if vanswer4== "4":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion5()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion5():
    global vscore
    global vtries
    vanswer5=input("Question 5. Guess which champ is called 'The Glorious Executioner'""\n"
                    "1. Draven" "\n"
                    "2. Teeto" "\n"
                    "3. Ivern" "\n"
                    "4. Diana")
    if vanswer5== "1":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion6()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion6():
    global vscore
    global vtries
    vanswer6=input("Question 6. What is the name of the newest champ that is going to be release soon?""\n"
                    "1. Ivern""\n"
                    "2. Ekko""\n"
                    "3. Jhin""\n"
                    "4. Camille")
    if vanswer6== "4":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion7()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion7():
    global vscore
    global vtries
    vanswer7=input("Question 7. What is supposed to be the rarest skin in League of Legends?""\n"
                   "1. PAX Twisted Fate""\n"
                   "2. Black Alistar""\n"
                   "3. King Rammus""\n"
                   "4. Human Ryze")
    if vanswer7== "3":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion8()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion8():
    global vscore
    global vtries
    vanswer8=input("Question 8. What is the name of the funky league animals that you can play in Legend of the Poro King?""\n"
                    "1.Pulu""\n"
                    "2.Poro""\n"
                    "3.Pokomo""\n"
                    "4.Teeto")
    if vanswer8== "2":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion9()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()


def vquestion9():
    global vscore
    global vtries
    vanswer9=input("Question 9. Which region is the champ Xerath part of?""\n"
                    "1.Shurima""\n"
                    "2.Piltover""\n"
                    "3.Noxus""\n"
                    "4.Demacia ")
    if vanswer9== "1":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion10()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()



def vquestion10():
    global vscore
    global vtries
    vanswer10=input("Question 10.Which champion is known as the 'Mechanized Menace'""\n"
                    "1. Kennen""\n"
                    "2. Rumble""\n"
                    "3. Viktor""\n"
                    "4. Kassadin")
    if vanswer10== "2":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion11()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion11():
    global vscore
    global vtries
    print("Question 11.Which champion has a move called 'Dredge Line'")
    vanswer11=input("1.Volibear""\n"
                    "2.Shen""\n"
                    "3.Nautilus""\n"
                    "4.Kog'Maw")
    if vanswer11== "3":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion12()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion12():
    global vscore
    global vtries
    vanswer12=input("Question 12. Nocturne is supposed to be the corrupted version of which champion? ""\n"
                    "1.Talon""\n"
                    "2.Rengar""\n"
                    "3.Xin Zhao""\n"
                    "4.Zed")
    if vanswer12== "4":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion13()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion13():
    global vscore
    global vtries
    vanswer13=input("Question 13. What is Nunu's ultimate called?""\n"
                    "1.Visionary""\n"
                    "2.Consume""\n"
                    "3.Ice Blast""\n"
                    "4.Absolute Zero")
    if vanswer13== "4":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion14()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

def vquestion14():

    global vscore
    global vtries
    vanswer14=input("Question 14. At Zed's level 3 ultimate, how much bonus AD does he steal from his target?""\n"
                    "1.+5%""\n"
                    "2.+7%""\n"
                    "3.+15%""\n"
                    "4.+10%""\n")
    if vanswer14== "3":
        print("\n""Correct""\n")
        vscore=vscore+1
        vquestion15()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

#If answer is right it will go to endscore function

def vquestion15():

    global vscore
    global vtries
    vanswer15=input("Question 15. What is Veigars description?""\n"
                    "1. The Tiny Devil""\n"
                    "2. Litte Master""\n"
                    "3. The Little Master of Evil""\n"
                    "4. One Shot Monster")
    if vanswer15=="3":
        print("\n""Correct""\n")
        vscore=vscore+1
        endscore()
    else:
        print("\n""Sorry that is incorrect""\n")
        vtries=vtries+1
        vscore=vscore-vscore
        restart()

#This will only show if all 15 questions are answered correctly it shows all information on the quiz.
#Also added a list called scoreboard so when I append the score to the scoreboard the name and rank will show
#Only if you press 1 it will add or else it will ask if you want to restart game again. If no the game will end.

def endscore():
    global totalscore
    print("Your score was", vscore,"\n")
    print("It took you",vtries,"tries to complete all questions""\n")
    totalscore=vscore-vtries
    print("Your total score is", totalscore,"\n")
    print("Here is your rank in league depending on your score...""\n")
    if totalscore==15:
        print("\n""YOU ARE A CHALLENGER!!!")
    elif totalscore==12 or 13 or 14:
        print("\n""YOU ARE A MASTER!!!")
    elif totalscore==10 or 11:
        print("\n""YOU ARE A DIAMOND!!")
    elif totalscore==8 or 9:
        print("\n""YOU ARE A PLAT!!")
    elif totalscore==6 or 7:
        print("\n""YOU ARE A GOLD!")
    elif totalscore<=5:
        print("\n""YOU ARE A BRONZE :(")
    vscoreboard=input("Do you want to put your score on the scoreboard? Press '1' if yes and '2' if no")
    if vscoreboard=="1":
        inventoryscore()
    else:
        print("Thanks for playing with us :)")
        gamerestart=input("Press '1' to restart game")

        if gamerestart=="1":
            print("\n""The game will now restart""\n")
        else:
            gamerestart=input("Press '1' to restart game")

            if gamerestart=="1":
                print("\n""The game will now restart""\n")
            else:
                exit()

#This is the list scoreboard where the name and rank will be added to a list, then restart question will
# be asked, if no exit, if yes restart.

def inventoryscore():
    scoreboard = []
    scoreboardname=input("Type your name and rank in this format: 'PLAYER 1:CHALLENGER': ")
    addname=scoreboard.append(scoreboardname)
    print("\n""Scoreboard:",scoreboard)
    gamerestart=input("Press '1' to restart game")
    if gamerestart=="1":
        print("The game will now restart")
        restart()
    else:
        exit()
#This is so the whole program works, have to put at bottom because the variables have to be
#above it or else there will be a syntax error.

title()
vname=input("Please enter your name here:Player1=")
print("\n""Hello",vname,"welcome to The Quiz on LOL a.k.a League of Legends, you will be tested on","\n","your knowlege of the game""\n")
print("\n""Press the 'Enter' key to sumbit your answer. If you answer a question incorrectly the game will restart from the first question... GOOD LUCK!!!""\n")
vquestion1()

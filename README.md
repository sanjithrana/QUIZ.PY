# QUIZ.PY
 This a computer quiz game.

print("Welcome to our computer quiz game...")

playing = input("Do you want to play? ")
score = 0

if playing.lower() != "yes":
    quit()

print("Okey! lets play..")

answer = input("what does CPU stands for? ")

if answer == "central processing unit":
    print("correct answer!   you scores 1 point")
    score +=1
else:
    print("Incorrect! you scores 0 point ")


answer = input("what does RAM stands for? ")

if answer == "random access memory":
    print("correct answer!   you scores 1 point")
    score +=1
else:
    print("Incorrect! you scores 0 point ")

answer = input("what does GPU stands for? ")

if answer.lower() == "graphics processing unit":
    print("correct answer!   you scores 1 point")
    score += 1
else:
    print("Incorrect! you scores 0 point ")



print("you scores "+str(score))
print("you scores "+str(score/3 * 100)+"%")


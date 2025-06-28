def intro():
  print("You have to go through a trivia about animals to win this game and earn a million dollars\nBut you need to get all the question sirght to earn all the money")
intro()
round1 = int(input("Welcome to Question 1! Remember you have to get every question correct. Choose the number next to the animal you choose as your answer.\n Question 1: What cat is the biggest cat in the world?\n1) Lion\n2) Jaguar\n3) Tiger\n4) Cheetahs "))
round2 = int(input("Now for question 2. What is the biggest animal on Earth?\n1) Elephant\n2) Eagle\n3) Great White shark\n4) Blue whale "))
round3 = int(input("Question 3. How many hearts does an octopus have?\n1) 8\n2) 1\n3) 2\n4) 5 "))
round4 = int(input("Question 4. What is the slowest animal in the world?\n1) Snail\n2) Sloth\n3) Slug\n4) Snake "))
round5 = int(input("Question 5. What is theastest bird in the world?\n1) Crow\n2) hawk\n3) Falcon\n4) owl "))
final1 = ""
final2 = ""
final3 = ""
final4 = ""
final5 = ""
if round1 == 1:
  final1 += "You chose a Lion that is incorrect"
elif round1 == 2:
  final1+= "You chose a jaguar that is incorrect"
elif round1 == 3:
  final1+="You chose a Tiger that is correct"
elif round1 == 4:
  final1 += "You chose a Cheetah that is incorrect"
if round2 == 1:
  final2+="You chose a Elephant that is incorrect"
elif round2 == 2:
  final2+="You chose a Eagle that is incorrect"
elif round2 == 3:
  final2+="You chose a Great White Shark that is incorrect"
elif round2 ==4:
  final2+="You chose a Blue Whale that is correct"
if round3 == 1:
  final3 += "You chose 8 that is correct"
elif round3 == 2:
  final3+= "You chose 1 that is incorrect"
elif round3 == 3:
  final3+="You chose 2 that is incorrect"
elif round3 == 4:
  final3 += "You chose 5 that is incorrect"
if round4 == 1:
  final4+="You chose a Snail that is incorrect"
elif round4 == 2:
  final4+="You chose a Sloth that is correct"
elif round4 == 3:
  final4+="You chose a Slug that is incorrect"
elif round4 ==4:
  final4+="You chose a Snake that is incorrect"
if round5 == 1:
  final5 += "You chose a Crow that is incorrect"
elif round5 == 2:
  final5+= "You chose a Hawk that is incorrect"
elif round5 == 3:
  final5+="You chose a Falcon that is correct"
elif round5 == 4:
  final5 += "You chose a Owl that is incorrect"

print(final1)
print(final2)
print(final3)
print(final4)
print(final5)
print("I hope you tried your best and be sure to play again for fun.")

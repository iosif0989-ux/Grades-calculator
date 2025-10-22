# Grades-calculator
#it can define what is your grade From A-F according your score between 0.0 and 1.0!
score =float(input("Enter Score: "))
if score>=0.0 and score<=1.0:
  if score >=0.9:
        print("A")
  elif score>=0.8 and score<0.9:
        print("B")
  elif score>=0.7 and score<0.8:
        print("c")
  elif score>=0.6 and score<0.7:
        print("D")
  else:
        print("F")
else:
    print("Error Message: Please give a number between 0.0 and 1.0")
    

    

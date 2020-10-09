# Trivia
print('Hello, welcome to my world')
ans = input('Are you ready to know about me?(yes/no)')
score=0
total_ques=5
if ans == 'yes':
    ans = input('1. What is my nickname?')
    if ans == 'kukku':
         score = score+1
         print('Correct')
    else:
         print('Incorrect')
ans = input('2. What is my favourite dish?')
    if ans == 'Chicken':
         score = score+1
         print('Correct')
    else:
         print('Incorrect')
ans = input('3. which outfits do I like: Western or Indian?')
    if ans == 'western':
         score = score+1
         print('Correct')
    else:
         print('Incorrect')'  
ans = input('4. Whom do I Love the most?')
    if ans == 'myself':
         score = score+1
         print('Correct')
    else:
         print('Incorrect')
ans = input ('5. What's my favourite movie?')
    if ans == 'Taare zameen par':
         score = score+1
         print('Correct')
    else:
         print('Incorrect')
print('Thanks for visiting', score, "questions correct")
marks = (score/total_ques)*100
print("Marks", str(marks) + %)
print('Bye take care')

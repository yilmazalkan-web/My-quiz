# My-quiz
simple capital city quiz
score = 0
Answer = input('What is the capital of Ireland ')
if Answer == 'Dublin' or 'dublin':
    print('Correct next question')
    score = score + 1

else:
    print('Incorrect')

answer2 = input('What is the capital of England ')

if answer2 == 'London' or 'london':
    print('Correct next question')
    score = score + 1

else:
    print('Incorrect')

answer3 = input('What is the capital of France ')

if answer3 == 'paris' or 'Paris':
    print('Correct next question')
    score = score + 1

else:
    print('Incorrect')

answer4 = input('What is the capital of Germany ')

if answer4 == 'berlin' or 'Berlin':
    print('Correct next question')
    score = score + 1

else:
    print('Incorrect')

answer5 = input('What is the capital of Spain ')

if answer5 == 'madrid' or 'Madrid':
    print('Correct next question')
    score = score + 1

else:
    print('Incorrect')

print('Welldone quiz complete your score was', score)

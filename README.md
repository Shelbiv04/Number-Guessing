# Number-Guessing
import random
lower_bound=1
upper_bound=100
max_attempts=10
random.randint(lower_bound, upper_bound)
def get_guess():
  while True:
    try: 
      guess = int(input(f"Guess a number between {lower_bound} and {upper_bound}

# hello-world

I am comm4ndercrunch
I am learning how to program
I need more caffeine

#Python version 3.5

number = 0

while number < 50:
  if number % 3 == 0 and number % 5 == 0:
    print(str(number) + ' fizzbuzz')
  elif number % 3 == 0:
    print(str(number) + ' fizz')
  elif number % 5 == 0:
    print(str(number) + ' buzz')
  else:
    print(number)
  number+=1

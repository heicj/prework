# prework

## codecademy Unit 3: PygLatin - part 10
```
pyg = 'ay'

original = raw_input('Enter a word:')


if len(original) > 0 and original.isalpha():
  word = original.lower()
  first = original[0]
  new_word = word + first + pyg
  new_word = new_word[1:len(new_word)]
  print original
else:
  print 'empty'
```

## codecademy Unit 4: Taking a Vacation - part 7

```
def hotel_cost(nights):
  return 140 * nights

def plane_ride_cost(city):
  if city == "Charlotte":
    return 183
  elif city == "Tampa":
    return 220
  elif city == "Pittsburgh":
    return 222
  elif city == "Los Angeles":
    return 475

def rental_car_cost(days):
  cost = days * 40
  if days >= 7:
    cost -= 50
  elif days >= 3:
    cost -= 20
  return cost

def trip_cost(city, days, spending_money):
  return hotel_cost(days) + plane_ride_cost(city) + rental_car_cost(days) + spending_money

print trip_cost("Los Angeles", 5, 600)
```

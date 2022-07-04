### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

  def check_for_ace(self, card):
    if card.value = 1:                  # Assignment instead of equality (= instead of ==)
      return True
    else                                # Colon missing
      return False
   

  dif highest_card(self, card1 card2):  # Not a function - typo (dif != def), comma missing from variables being passed into function.
  if card1.value > card2.value:         # Indentation required to be inside function
    return card                         # Card not defined - likely typo and should be card1
  else:
    return card2
  


def cards_total(self, cards):               # Not inside class
  total                                     # Total not assigned a value
  for card in cards:
    total += card.value
    return "You have a total of" + total    # Return inside for loop / Can't concatenate a string and integer, would need conversion. 
  
```

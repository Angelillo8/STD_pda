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
    # There is missing "=". It should be if card.value == 1:
    if card.value = 1:
      return True
    # There is a missing ":"
    else
      return False
   
# It should be def instead of dif, and there is a missing comma 
# betweend card1 and card 2 inside the parethesis.
  dif highest_card(self, card1 card2):
  # From the if to the last return should be indented 
  if card1.value > card2.value:
    # It should return card1.
    return card
  else:
    return card2
  

# The whole function should be indented. 
def cards_total(self, cards):
  # total needs to be initialized with 0. total = 0
  total
  for card in cards:
    total += card.value
    # It needs to be str(total)
    # It also needs to be returned one indent.
    return "You have a total of" + total
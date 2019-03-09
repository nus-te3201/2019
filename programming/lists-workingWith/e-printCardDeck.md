#### Exercise : Print Card Deck

Complete the functions as described below:
* `print_card_deck()`: Prints all cards in a deck of regular playing cards, en example of the output (partial) is given below.


<table>
<tr>
  <td>

```python
def print_card_deck():
  suits = ['♣', '♦', '♥', '♠']
  ranks = ['A', '2', '3', '4', '5', '6', '7', '8', '9', '10', 'J', 'Q', 'K']
  
print_card_deck()

```
  </td>
  <td>&nbsp;→&nbsp;</td>
  <td>
  
```
A of ♣
2 of ♣
3 of ♣
4 of ♣
5 of ♣
6 of ♣
...

```
  </td>
</tr>
</table>

<panel type="seamless" header="%%:bulb: Hint%%">

Use two nested `for` loops to iterate over the two lists.

</panel>

<panel type="seamless" header="%%:bulb: partial solution%%">

```python
  ...
  for suite in suits:
    for ...:
      print(...)
```
</panel>
#### Exercise - Vending Machine - Legit Coins

The vending machine you wrote in the previous exercise (an example solution given below) accepts any value as the coin value. However, coins come in only certain values only.
```python
price = 100
coin_sum = 0
is_aborting = False

print('Price:', price)

while price > coin_sum:
  coin_value = int(input('Enter a coin:'))
  if coin_value == 0:
    is_aborting = True
    break
  coin_sum = coin_sum + coin_value
  print('You have entered:', coin_sum)

if is_aborting:
  print('Your balance:', coin_sum)
else:
  print('Here is the product')
  print('Your balance:', coin_sum - price)
```

Modify the code so that it accepts coins of value 10, 20, 50, 100 only:

```
Price: 100
Enter a coin: 30
Coin not recognized
Enter a coin: 100
You have entered: 100
Here is the product
Your balance: 0
```

<panel type="seamless" header=":bulb: see hint">

```python
...
if coin_value != 10 and ... :
    ...
    continue
...
```
</panel>
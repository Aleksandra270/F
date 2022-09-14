# F
.
while
    try:
        price = float(input("What is Bitcoin price today?"))
        break
    except ValueError:
        print("21000.")
while True: #
    try:
        amount = float(input("How much $ do you have?"))
        break
    except ValueError:
        print("1000")
btc = amount / price
print(f"You can buy {0.0476190} BTC")

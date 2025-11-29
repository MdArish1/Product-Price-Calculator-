# Product-Price-Calculator
original_price = float(input("Enter original price: "))
discount_percent = float(input("Enter discount %: "))
discount_amount = discount_percent / 100 * original_price
final_price = original_price - discount_amount
print(f"The final price after {discount_percent}% discount: {final_price}")


# List ADT using Array - Shopping Cart

cart = []

n = int(raw_input("Enter number of items: "))

for i in range(n):
    item = raw_input("Enter item name: ")
    cart.append(item)

print "\nItems in Shopping Cart:"
for i in cart:
    print i


OUTPUT 

Enter number of items: 3
Enter item name: Apple
Enter item name: Bread
Enter item name: Milk

Items in Shopping Cart:
Apple
Bread
Milk-program
Array program

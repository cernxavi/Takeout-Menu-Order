# Takeout Ordering System

This Python program simulates an ordering system for a takeout restaurant. It allows customers to browse a menu, select items, specify quantities, and receive an itemized receipt with the total cost.

---

## Features
- Displays a structured menu with categories, meals, and prices.
- Allows customers to select menu items by number.
- Accepts multiple orders in a single session.
- Calculates and displays an itemized receipt.
- Handles invalid inputs gracefully, ensuring a smooth user experience.

---

## Example Menu
Below is an example of the menu structure used in the program:

```
Burrito
    - Chicken: $4.49
    - Beef: $5.49
    - Vegetarian: $3.99
Rice Bowl
    - Teriyaki Chicken: $9.99
    - Sweet and Sour Pork: $8.99
Sushi
    - California Roll: $7.49
    - Spicy Tuna Roll: $8.49
```

---

## Key Functions

### `place_order(menu)`
Handles the entire ordering process:
- Displays the menu.
- Captures user selections.
- Calculates the total cost.

### `update_order(order, menu_selection, menu_items)`
Validates the user's menu selection and adds the item to the order.

### `print_itemized_receipt(receipt)`
Prints an itemized receipt with item names, prices, quantities, and the total.

### `get_menu_items_dict(menu)`
Generates a dictionary mapping menu item numbers to item details (name and price).

---

## Sample Output
```
Welcome to the Generic Take Out Restaurant.
--------------------------------------------------
Item # | Item name                        | Price
-------|----------------------------------|-------
1      | Burrito - Chicken                | $4.49
2      | Burrito - Beef                   | $5.49
3      | Burrito - Vegetarian             | $3.99
...
What would you like to order?
Please enter the number of the item you would like to order: 1
How many Burrito - Chicken would you like to order? 2
Would you like to order anything else? (y/n): n
Thank you for your order!

This is what we are preparing for you.
----------------------------------------------------
Item name                       | Price  | Quantity
--------------------------------|--------|----------
Burrito - Chicken               | $4.49  | 2
----------------------------------------------------
Total price: $8.98
----------------------------------------------------
```

---

## Github
Repo: https://github.com/cernxavi/Takeout-Menu-Order.git

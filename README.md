# LAB_OOP_01

## Coffee Shop Menu

### Scenario

You are developing a simple system for a coffee shop. The shop sells different drinks, and each drink has its own name, price, and size.

Your task is to create a Python class that represents a drink and allows the coffee shop to display information and update its price.

### Requirements

1\. Create a class named `Drink`

Each drink should have the following attributes:

- `name` — The name of the drink.
- `price` — The price in SAR.
- `size` — The size of the drink (Small, Medium, or Large).

2\. Create the following methods

| Method                       | Description                                        |
| ---------------------------- | -------------------------------------------------- |
| `display_info()`             | Displays the drink's name, size, and price.        |
| `change_price(new_price)`    | Updates the drink's price.                         |
| `apply_discount(percentage)` | Reduces the drink's price by the given percentage. |

3\. Create objects

Create three different drinks using the `Drink` class:

| Name       | Size   | Price  |
| ---------- | ------ | ------ |
| Latte      | Medium | 18 SAR |
| Espresso   | Small  | 12 SAR |
| Cappuccino | Large  | 22 SAR |

4\. Perform the following operations

1. Display the information of all three drinks.
2. Change the Latte's price to 20 SAR.
3. Apply a 25% discount to the Cappuccino.
4. Display the updated information for the Latte and Cappuccino.

### Expected Output

Console

```
=== Coffee Shop Menu ===
Latte (Medium) - 18 SAR
Espresso (Small) - 12 SAR
Cappuccino (Large) - 22 SAR

=== Updated Menu ===
Latte (Medium) - 20 SAR
Cappuccino (Large) - 16.5 SAR
```

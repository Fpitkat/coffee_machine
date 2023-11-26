# Coffee Machine Program Requirements

This README outlines the requirements and functionality of a Coffee Machine program. The program is designed to simulate the operation of a coffee vending machine. It interacts with the user, processes their choices, manages resources, and provides beverages in exchange for money. Below are the key functionalities and requirements of the program:

## 1. User Interaction

- The program should prompt the user with the message: "What would you like? (espresso/latte/cappuccino):"
- The prompt should reappear after each action is completed to serve the next customer.

## 2. Turning Off the Coffee Machine

- To turn off the Coffee Machine, the user can enter "off" as the input.
- When "off" is entered, the program should terminate its execution.

## 3. Printing a Report

- If the user enters "report" as the input, a report should be generated, displaying the current resource values, including:
  - Water in milliliters (ml)
  - Milk in milliliters (ml)
  - Coffee in grams (g)
  - Money in dollars ($)

## 4. Checking Resource Availability

- Before preparing a drink, the program should check if there are sufficient resources to make that drink.
- If any of the required resources (water, milk, coffee) are depleted, the program should print a message indicating the resource shortage.

## 5. Processing Coins

- If there are enough resources, the program should prompt the user to insert coins.
- The program should accept the following coin denominations:
  - Quarters ($0.25)
  - Dimes ($0.10)
  - Nickels ($0.05)
  - Pennies ($0.01)
- It should calculate the total monetary value of the coins inserted by the user.

## 6. Checking Transaction Success

- After counting the inserted coins, the program should check if the user has inserted enough money to purchase the selected drink.
- If the user's inserted coins are insufficient to cover the cost of the drink, the program should refund the money and print a message.

## 7. Making Coffee

- If the transaction is successful and there are enough resources, the program should proceed to make the chosen drink.
- The ingredients required to make the drink should be deducted from the coffee machine's resources.
- Once all resources are deducted, the program should inform the user by printing: "Here is your [drink]. Enjoy!" where [drink] is the user's choice.

These requirements outline the main functionality and user interactions expected from the Coffee Machine program. By following these guidelines, you can create a coffee vending machine simulator that provides a user-friendly experience and manages resources efficiently.

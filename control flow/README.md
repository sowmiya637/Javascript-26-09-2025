# Online Food Order - Simple Web App


This is a basic **Online Food Order** web application that lets users select a dish, enter quantity, and get the total price along with applicable discounts. It demonstrates the use of JavaScript **control flow** statements like `switch`, `if-else`, and the **ternary operator** to calculate price and apply discounts dynamically.


- User can select from a list of dishes: Pizza, Burger, Pasta, Biryani, Ice Cream.
- User enters the quantity for the selected dish.
- Price per dish is determined using a `switch` statement.
- Calculates the total amount based on price and quantity.
- Applies discounts based on the total amount:
  - 20% discount if total ≥ ₹500
  - 10% discount if total ≥ ₹300 and < ₹500
  - No discount if total < ₹300
- Displays an order summary with:
  - Dish name (in uppercase)
  - Quantity
  - Price per item
  - Total price before discount
  - Discount amount and percentage
  - Final amount to be paid
  - Message indicating discount status (using ternary operator)

## Code Structure

- **HTML**: Structure of the webpage including form controls and output area.
- **CSS**: Styling for layout, colors, fonts, buttons, and responsive behavior.
- **JavaScript**:
  - Retrieves user input.
  - Uses `switch` to set dish price.
  - Checks dish availability.
  - Calculates total price and discount.
  - Uses ternary operator to generate discount message.
  - Displays final order summary.


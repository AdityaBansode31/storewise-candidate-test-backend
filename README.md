## Welcome to the Storewise Tech Screening Challenge

### Setup Instructions
- Ensure that you have [python3](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installation/) installed in your machine
- Clone this repository
- `cd` into the new directory (that you cloned)
- `pip install bullet`
- `python3 main.py`


3. **Follow the Prompts:**
   - Add items and beverages to your order as prompted.
   - The application will display a final bill with the total amount and service charge.

## Code Overview

- **`main.py`**: Contains the main logic for ordering, calculation, and displaying the bill.
- **`PurchaseItem`**: Represents an item purchased by the user.
- **`Option`**: Represents a menu option (food or beverage).
- **`get_total_order_amount(order: List[PurchaseItem])`**: Calculates the total cost of the order.
- **`get_service_charge(order: List[PurchaseItem])`**: Calculates the service charge based on the order amount.

## Screenshots

### Initial Menu
![initial_menu](https://github.com/user-attachments/assets/f6f962f3-9f7d-4568-953a-d8cf5cb79326)
*Description:* The starting screen where users can select food items.


### Ordering Items
![ordering_items](https://github.com/user-attachments/assets/203ff794-f407-41b3-9ee3-0f294f58fae1)
*Description:* The interface showing items added to the order.

### Final Bill
![final_bill](https://github.com/user-attachments/assets/9679b07a-3f79-43ff-ba01-a01135bad850)
*Description:* The final bill summary displaying the order amount, service charge, and total amount.


## Acknowledgments

- Thank you for the opportunity to work on this assignment.
- Utilizes the `bullet` library for enhanced shell-based interaction.

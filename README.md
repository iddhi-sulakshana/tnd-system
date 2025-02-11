# tnd-system

-   TODO: Cheques for Suppliers
-   TODO: Product linkage like Laminating papers are linked with the laminating
-   TODO: When Adding Quantity if stock details are same increase the quantity instead of creating a new batch
-   TODO: Timzone is showing in UTC check for that

# Roles

-   Admin
-   Managers
-   Cashiers

# User Stories

-   [x] Login Functionality to the system for all the Users.
    -   [x] Admin
    -   [x] Managers
    -   [x] Cashiers
-   [ ] When something tries to delete ask for user confirmation modal.
-   [ ] When something deletes from the database try not to delete it but mark it as deleted for other references to get the values from the database.

## Admin

-   [x] When System is running for the first time user need to add relevant details for the Company and the Admin details.
-   [ ] Manage Cashiers and Managers (Add / Delete / Edit)
-   [x] Export the data from the system / create backup.
-   [x] Restore the data from the backup.
-   [ ] Should be able to update the company details on the settings page.

## Managers

-   [x] Manage Products (Add / Delete / Edit)
-   [x] Manage Inventory Stocks for the Products.
-   [ ] Update the Stocks inventory - would it be useful to scan the barcode then show quantity then show "✓", "x" to confirm the stock or update it.
-   [x] Apply minimum stock levels for the inventory.
-   [ ] Notify when minimum stock level reached its minimum.
-   [ ] Track sales record.
-   [ ] Generate daily, weekly, monthly, yearly reports.
-   [ ] View the best selling items.
-   [ ] View profit margins for the individual product.
-   [x] Set initial amount of the cash register in the begining of the day.
-   [ ] Initiate order refund.
-   [ ] View customers purchase history.
-   [ ] Accept cash withdrawals from the cash register.
-   [ ] Accept cash deposit to the cash register.
-   [ ] End of the day reconcile cash in register with the transactions to the actual cash in the register.
-   [ ] View cash reconcilation to identify errors in cash handling.
-   [ ] In the end of the day view a detailed audit trail of all cash movements (withdrawals, Deposits, Transactions)
-   [x] Delete customers from the system.
-   [x] Manage Suppliers (Add / Edit / Delete)
-   [ ] Manage Purchase orders from the suppliers for the inventory.
-   [ ] Add Cheques as payment method for the purchase orders.
-   [ ] Notify when cheque due date is coming.
-   [ ] Refund the customer bill.

## Cashiers

-   [x] Scan the barcode and it will quickly add product to the order.
-   [x] Search by the product name or barcode to add to the bill.
-   [x] View previous orders.
-   [ ] Apply discounts to the bill.
-   [x] Apply discounts to the individual item.
-   [x] Multiple payment methods (Cash, Card)
-   [x] Print a reciept of a bill
-   [x] Hold and Resume orders
-   [x] Select a customer for a order
-   [x] Manage Customers (Add / Edit)
-   [ ] View the current cash amount in the register.
-   [x] Request withdrawal from the cash register.
-   [x] Request deposit to the cash register.
-   [ ] Follow ups to do track the reconcilation of missing cash.
-   [x] Send Automatic WhatsApp message of the order details to the customer.
-   [x] Send Automatic Email message of the order details to the customer.
-   [ ] In the POS window most used products should be in the top of the page for easy access.

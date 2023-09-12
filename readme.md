--- POS Inventory ---

last update: 8/21/2023
changes:
notification number updating
Product.php line 211, 216, 236, 241, 261, 266 

**** Boolean notes of column in each table ****

Users table
 * role
    1 = owner
    2 = admin
    3 = user
 * status
    1 = active
    2 = inactive

Invoices table
 * discount
    1 = Yes
    0 = No

Product_details table
 * expired_status
    4 = Decompose
    3 = For Return
    2 = For exchange
    1 = Yes
    0 = No

Products table
 * status
    1 = Active
    0 = Inactive
 * Type
    1 = Branded
    0 = Generic
    null = <No Type>
 * stock status
    0 = out of stock
    1 = normal stock
    2 = under stock
    3 = over stock
    

Sales table
  * void
    1 = Void
    0 = Not Void





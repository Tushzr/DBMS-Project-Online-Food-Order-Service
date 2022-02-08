# DBMS-Project-Online-Food-Order-Service

### Description
This is a simple Java online food ordering service application. </br>
The main purpose of this project is to mimic the working of a commercial online food order app. </br>
It consists of a login/create account page, a menu to choose food items, and options to display/delete items in wishlist/cart/orders. </br>

### Applications/Development environment used
<ul>
  <li> Java(TM) SE Runtime Environment (build 17.0.1+12-LTS-39) </li>
  <li> MySQL 8.0 </li>
  <li> Microsoft Visual Studio Code v1.64.0
</ul>

#### The output is as follows:
```

--------------------------------------------------
|           Online Food Order Service            |
--------------------------------------------------
|                    1. Login                    |
|                2. Create account               |
|                    3. Exit                     |
--------------------------------------------------
Enter choice: 1
Enter username: ok
Enter password: ok

Invalid username/password.

--------------------------------------------------
|           Online Food Order Service            |
--------------------------------------------------
|                    1. Login                    |
|                2. Create account               |
|                    3. Exit                     |
--------------------------------------------------
Enter choice: 2
Enter username: ok
Enter password: ok

Account created successfully.

--------------------------------------------------
|           Online Food Order Service            |
--------------------------------------------------
|                    1. Login                    |
|                2. Create account               |
|                    3. Exit                     |
--------------------------------------------------
Enter choice: 1
Enter username: ok
Enter password: ok

Invalid username/password.

Welcome ok!

-------------------------
|          MENU         |
-------------------------
|1. Buy food            |
|2. View wishlist       |
|3. View cart           |
|4. View orders         |
|5. Exit to login page  |
-------------------------
Enter choice: 2

Wishlist is empty.
-------------------------
|          MENU         |
-------------------------
|1. Buy food            |
|2. View wishlist       |
|3. View cart           |
|4. View orders         |
|5. Exit to login page  |
-------------------------
Enter choice: 3

Cart is empty.
-------------------------
|          MENU         |
-------------------------
|1. Buy food            |
|2. View wishlist       |
|3. View cart           |
|4. View orders         |
|5. Exit to login page  |
-------------------------
Enter choice: 4

No orders placed.
-------------------------
|          MENU         |
-------------------------
|1. Buy food            |
|2. View wishlist       |
|3. View cart           |
|4. View orders         |
|5. Exit to login page  |
-------------------------
Enter choice: 1

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 1
Add to - 1. Cart, 2. Wishlist: 2
Enter quantity: 2

Item added successfully.

Choose an item (sno) to add to cart or wishlist: 
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 2
Add to - 1. Cart, 2. Wishlist: 2
Enter quantity: 2

Item added successfully.

Choose an item (sno) to add to cart or wishlist: 
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 3
Add to - 1. Cart, 2. Wishlist: 2
Enter quantity: 3

Item added successfully.

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 7

                           WISHLIST
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|2    |ITEM 2              |2                   |300                 |
|3    |ITEM 3              |3                   |525                 |
----------------------------------------------------------------------

1. Remove item from wishlist
2. Remove all items from wishlist
3. Add all items to cart
4. Return to items menu
Enter choice: 1
Enter ID of item to remove: 2

Item successfully removed from wishlist.

                           WISHLIST
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|3    |ITEM 3              |3                   |525                 |
----------------------------------------------------------------------

1. Remove item from wishlist
2. Remove all items from wishlist
3. Add all items to cart
4. Return to items menu
Enter choice: 3

Items added to cart.

                           WISHLIST
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|3    |ITEM 3              |3                   |525                 |
----------------------------------------------------------------------

1. Remove item from wishlist
2. Remove all items from wishlist
3. Add all items to cart
4. Return to items menu
Enter choice: 2

All items removed from wishlist successfully.

Wishlist is empty.

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 8

                               CART
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|3    |ITEM 3              |3                   |525                 |
----------------------------------------------------------------------
                                                Total: 725
1. Remove item from cart
2. Remove all items from cart
3. Checkout
4. Return to items menu
Enter choice: 4

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 4
Add to - 1. Cart, 2. Wishlist: 2
Enter quantity: 4

Item added successfully.

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 8

                               CART
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|3    |ITEM 3              |3                   |525                 |
----------------------------------------------------------------------
                                                Total: 725
1. Remove item from cart
2. Remove all items from cart
3. Checkout
4. Return to items menu
Enter choice: 4

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 7

                           WISHLIST
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|4    |ITEM 4              |4                   |900                 |
----------------------------------------------------------------------

1. Remove item from wishlist
2. Remove all items from wishlist
3. Add all items to cart
4. Return to items menu
Enter choice: 3

Items added to cart.

                           WISHLIST
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|4    |ITEM 4              |4                   |900                 |
----------------------------------------------------------------------

1. Remove item from wishlist
2. Remove all items from wishlist
3. Add all items to cart
4. Return to items menu
Enter choice: 2

All items removed from wishlist successfully.

Wishlist is empty.

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 8

                               CART
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|3    |ITEM 3              |3                   |525                 |
|4    |ITEM 4              |4                   |900                 |
----------------------------------------------------------------------
                                                Total: 1625
1. Remove item from cart
2. Remove all items from cart
3. Checkout
4. Return to items menu
Enter choice: 3

Order successfully placed.

Cart is empty.

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 9

                             ORDERS
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|3    |ITEM 3              |3                   |525                 |
|4    |ITEM 4              |4                   |900                 |
----------------------------------------------------------------------
                                                Total: 1625
1. Cancel orders
2. Cancel all orders
3. Return to items menu
Enter choice: 1
Enter ID of order to cancel: 4

Order cancelled.

                             ORDERS
----------------------------------------------------------------------
|ID   |Item name           |Quantity            |Item total          |
----------------------------------------------------------------------
|1    |ITEM 1              |2                   |200                 |
|3    |ITEM 3              |3                   |525                 |
----------------------------------------------------------------------
                                                Total: 725
1. Cancel orders
2. Cancel all orders
3. Return to items menu
Enter choice: 2

All orders cancelled successfully.

No orders placed.

Choose an item (sno) to add to cart or wishlist:
-------------------------------------------------
|Sno. |Item name           |Price               |
-------------------------------------------------
|1    |ITEM 1              |100                 |
|2    |ITEM 2              |150                 |
|3    |ITEM 3              |175                 |
|4    |ITEM 4              |225                 |
-------------------------------------------------
|7. View wishlist                               |
|8. View cart                                   |
|9. View orders                                 |
|0. Exit to main menu                           |
-------------------------------------------------
Enter choice: 0
-------------------------
|          MENU         |
-------------------------
|1. Buy food            |
|2. View wishlist       |
|3. View cart           |
|4. View orders         |
|5. Exit to login page  |
-------------------------
Enter choice: 5

--------------------------------------------------
|           Online Food Order Service            |
--------------------------------------------------
|                    1. Login                    |
|                2. Create account               |
|                    3. Exit                     |
--------------------------------------------------
Enter choice: 3
```

#### Sample changes done to database while running the application:
```
mysql> SELECT * FROM USERS;
+----------+----------+
| USERNAME | PASSWORD |
+----------+----------+
| user1    | user1    |
| user2    | user2    |
+----------+----------+
2 rows in set (0.01 sec)

mysql> SELECT * FROM ITEMS;
+----------+-------+
| ITEMNAME | PRICE |
+----------+-------+
| ITEM 1   |   100 |
| ITEM 2   |   150 |
| ITEM 3   |   175 |
| ITEM 4   |   225 |
+----------+-------+
4 rows in set (0.00 sec)

mysql> SELECT * FROM USER1_WISHLIST;
+----+----------+------+-------+
| ID | ITEMNAME | QTY  | PRICE |
+----+----------+------+-------+
|  1 | ITEM 1   |    3 |   300 |
|  2 | ITEM 2   |    3 |   450 |
|  3 | ITEM 3   |    4 |   700 |
+----+----------+------+-------+
3 rows in set (0.01 sec)

mysql> SELECT * FROM USER1_CART;
+----+----------+------+-------+
| ID | ITEMNAME | QTY  | PRICE |
+----+----------+------+-------+
|  6 | ITEM 1   |    3 |   300 |
|  7 | ITEM 3   |    2 |   350 |
+----+----------+------+-------+
2 rows in set (0.00 sec)

mysql> SELECT * FROM USER1_ORDERS;
+----+----------+------+-------+
| ID | ITEMNAME | QTY  | PRICE |
+----+----------+------+-------+
|  4 | ITEM 4   |    2 |   450 |
|  5 | ITEM 3   |    5 |   875 |
+----+----------+------+-------+
2 rows in set (0.00 sec)

mysql> SELECT * FROM USER2_WISHLIST;
Empty set (0.01 sec)

mysql> SELECT * FROM USER2_CART;
Empty set (0.01 sec)

mysql> SELECT * FROM USER2_ORDERS;
Empty set (0.01 sec)
```

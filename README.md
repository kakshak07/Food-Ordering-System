# Food Ordering System

Food Ordering System is an application which will help restaurant to optimized and control over their restaurants. For the waiters, it is making life easier because they don’t have to go kitchen and give the orders to chef easily. For the management point of view, the manager will able able to control the restaurant by having all the reports to hand and able to see the records of each employees and orders. This application helps the restaurants to do all functionalities more accurately and faster way. Food Ordering System reduces manual works and improves efficiency of restaurant. This application is helping Food Ordering s to maintain the stock and cash flows and there are many more functionalities, like. 

1. To store records.  Control orders and services.  Billings.  Control staff and their shifting. 
2. Control multiple branches.  Helps Manager to control each part of the restaurant. The main goal is to maintain the restaurant’s functions in an effective and accurate manner and also it is reducing the use of manual entries. This software helps food orders to maintain day to day records in system. It is keeping a proper record of the database.

PROBLEM STATEMENT: Many restaurants is storing all of their data in manual way. They have huge number of customers daily. So because large number of customers, they need the help of some features so they can maintain and stores the records accurately. 
## Screenshots
### Login
![Login](https://image.prntscr.com/image/aY4ghnqETTWc8w6RRqcSOw.jpg)
### Register
![Register](https://image.prntscr.com/image/B67umVCPSae_38Gfenxlbw.jpg)
### Modify Food Menu (Admin)
![Modify Menu](https://image.prntscr.com/image/bAoF4lB7THOSZ-9zI5eXzg.jpg)
### Food Menu (Customer)
![View tickets](https://image.prntscr.com/image/dEVkeAVhRxWbxCu_uNB5ew.jpg)
### Placing Order
![Records](https://image.prntscr.com/image/QSWkwRmNSkOnL9TrrfkpJA.jpg)
### View all Orders(Admin)
![Records](https://image.prntscr.com/image/QsUxzm5nTRatVyt5PY-xNg.jpg)
### List Tickets
![View All Tickets(Admin)](https://image.prntscr.com/image/8cr_-H4wRQC3HxOVBQseFA.jpg)
### Place & View Tickets(Customer)
![Tickets(User)](https://image.prntscr.com/image/M_VIy9bRQCe9eYFsn4AWUA.jpg)
### Communicating on Support Ticket
![Support Ticket](https://image.prntscr.com/image/aR7kQo5AQpSa_Y3kU3SDcA.jpg)
### Modify Details(Customer)
![Modifying Records](https://image.prntscr.com/image/sXogBp55SMahRleBIv7Plg.jpg)
### User Management(Admin)
![Modifying Records](https://image.prntscr.com/image/St11KReLQVOXHctcmsHY-g.jpg)


How To Install -
---------

1. Create Database food.
2. Run food.sql script provided in sql folder.
3. Go to login.php and try out our application. Sample user credentials can be found in users & wallet_details table.

Note -
---------
1. This is not ready for PRODUCTION.
2. The username and password of sample users are stored in table `users`.
3. Only Customers with "Verified" status can place orders using "Cash on Delivery" option.
4. By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
5. Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
6. What's lacking? Dynamic payment(real payment system) and error reporting lacks in this project. And also one might wish for showing corresponding food item's photo and all that stuff.

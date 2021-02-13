# E-Pharmacy-Website

DESCRIPTION:
Ordering system: 
Customer has to register first and then login. He will be then directed to
authenticated user page. Any customer will be able to view the product details
like product name, description, image, price, available quantity and category.
Selected products will be added to cart. The customer can order the products and
after payment details the order details are stored and an email is sent to user
along with order id.

Cancelation –
Customer can cancel ordered products before order is shipped. Email is sent to
user after product is cancelled.

Specialization –
According to number of times each customer orders discount will be given. For
eg: If a customer has more than 5 previous orders then he/she will get a discount
of 10% on next orders.

Admin –
The admin will be able to view the customer profiles. He/She can add and decide
the quantity. The admin will also be able to check and update the order status of
customer’s orders.


Database overview

User Profile -
Username, User-id, email, contact, Password, user role(admin,user)

Product –
Id, category id, name, description, image, price, available quantity, supplier id
Supplier –

Supplier id, supplier name
3
Cart –

order id, product id, price, quantity, ptotal

Order –
order id, total price, date, customer id, address, order_status

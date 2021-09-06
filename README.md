# Inventory-Management-System
This is a project given under the Python for AI/ML internship by Elite Techno Groups. Here, I have created a model of Inventory Management System.

Functionalities:

-> main()
-> userMain()
    -> viewInventory()
    -> addProductToCart(cart)
    -> removeProductFromCart(cart)
    -> viewcart(cart)
    -> payBill(cart)
    
-> adminMain()
    -> viewInventory()
    -> addToInventory()
    -> viewOrders()
    -> viewStatistics()
    
Utility Functions:
-> price(cart)
-> viewCart(cart)
-> load(fileName)
-> saveInOrders(cart)
-> saveInJson(filename,dictionary)


Descriptions:
main() - IMS can be accessed as the admin or as a customer. 

userMain() - For accessing customer's functionalities which are :
    -> viewInventory() - for viewing the items available in the inventory
    -> addProductToCart() - adding product to the cart
    -> removeProductFromCart() - used to remove product from cart
    -> viewCart() - for viewing the items currently in the cart
    -> paybill() - for payment of every item in the cart

adminMain() - For accessing admin's functionalities which are :
    -> viewInventory() - for viewing the items available in the inventory
    -> addToInventory() - for adding items to stock
    -> viewOrders() - for viewing an overview of all the item sold
    -> viewStatistics() - graphical representation of sales per item

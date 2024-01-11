It is an E-commerce system built in Django. It contains all the essentials for adding products and use PayPal to pay for the purchase. 

#### The Business Objectives

1. To develop an online presence.
2. Increase business awareness.
3. Expand the target audience reach.
4. To showcase the products business sell.
5. Provide easily accessible information to customers.
6. To develop online communication with our customer base.

#### Customer Objectives

1. To gain access to business information.
2. To access business and buy stuff.
3. To be able to get add and remove products from the cart.
4. To see the total in cart.
5. Easily pay for the products.

##### Future goals

* Ability to develop a complete full store with different products and information about the store.
* To develop a system so that customer join online and earn points by membership.
* To Create further pages for a complete working site.

## UX

This application is for customers, to provide a small number of products. 


### Functionality

1. User- Built in Django user model. An instance of this model will be created for each customer that registers with our website. This model will give us the ability to later use Djangos default authentication system without having to manually set this up ourselves.

2. Customer - Along with a User model each customer will contain a Customer model that holds a one to one relationship to each user. (OneToOneField). 

3. Product - The product model represents products we have in store.

4 .Order - The order model will represent a transaction that is placed or pending. The model will hold information such as the transaction ID, data completed and order status. This model will be a child or the customer model but a parent to Order Items.

5 .OrderItem- An order Item is one item with an order. So for example a shopping cart may consist of many items but is all part of one order. Therefore the OrderItem model will be a child of the PRODUCT model AND the ORDER Model.

6. ShippingAddress- Not every order will need shipping information. For orders containing physical products that need to be shipping we will create an instance of the shipping model to know where to send the order. Shipping will simply be a child of the order model when necessary.

## Features

* Store
* Cart
* Checkout
* Shipping
* Payment Option

### Features Left to Implement

- online system to join 
* membership

## Technologies Used

* Django (latest Version-4.0)
* CSS
* Bootstrap
* Basic HTML
* Javascript

## Testing

* The project has been tested thoroughly to the best of my knowledge. The navbar has been functional. 
* The desktop version of the project has been working.
* The mobile version is working.
* The CSS has been validated by W3Schools Validator and no error was found.

<p>
<a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="Valid CSS!" />
    </a>
</p>

## Credits

* Codeinstitute tutorials 
* Google Images 
* w3school


### Content

* The images has been taken from google images .
* [W3Schools](w3schools.com) is used to get help for the project.


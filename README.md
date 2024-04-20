# EcommerceSystem
We have the first super class which is called Product.
It has 3 subclasses ; Electronic Product, Clothing Product, Book Product.
Used private methods in order to limit access to the constructors (Product Id, Name,Price).
Used setters and getters to set and return values + used Math.abs function to take absolute integer or float values.

The first subclass is Electronic Product, it inherits the super class features adding to its own methods Brand and warranty period.
Used setters and getters to set and return values.

The second subclass is Clothing Product, it inherits the super class features adding to the size and fabric methods.
Used setters and getters to set and return values.

The third subclass is Book Product , it inherits superclass features adding to the author and publisher methods.
Used stters and getters to set and return values.

Then we have the Customer class, it is a seperate class where we have the customerId,name,address to use them while placing the order.
Used stters and getters to set and return their values.

Class Cart is a class used for preparing the cart where the customer will add his/her order in.
we use the customer Id, number of products & array to count the order starting with element 0.
we create a method to add product and we add to the index of array 1.
another method to remove product adding if-condition if the index if more than 0&&less than the no of products
,then it will go inside a for loop to decrease the index by one.
the last method to calculate price where we add the total price of products then use the getters to get and return final price.

Then the last class order, used setters and getters to take all the required info from the customer which are 
(Cst Id,Order Id,Products,TotalPrice)
Print statements to give the order summary ,display the order id,customer id,products, and the total price.

Then the main class, we defined the three products, used their attributes,and created instances for the objects like the smartphone,tshirt and book with predefined details.
Used scanner object to get input from user, then use information to create a customer and ask the user how many products they want to order.
Then we use a loop to iterate for the number of products chosen, and add the coressponding products to the user's cart.
if invalid choice is chosen, then we skip a product during iteration.
then while proceeding to check out it displays the total price and ask user a yes or no question.
if yes is chosen then the payment system is activated if no then order is cancelled.

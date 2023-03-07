## Task 2

- Find Out top selling 
* Create a Cart module that will manage a set of cart items. Each cart item will have the following information associated with it.

1. Product ID
2. Title
3. Unit price
4. Quantity
5. Discount code
6. Item total price

### The cart module should support the following features.
1. Add a cart item
- If the item already exists then the quantity of that should increase.
- Users of this class should be able to increase the quantity of an item by one or more at a time.
2. Remove a cart item
- Users of this class should be able to decrease the quantity of an item by one or more at a time.
3. Apply Discount Code to a cart item
- Each discount code should have an associated percentage with it.
- Keep all the discount codes in someplace. No need to have the functionality to add/remove discount codes. They can be statically defined.
- When applying for a discount code, you should get the discount code from there.
4. Apply Discount code to the whole cart
- Not all discount codes should be applicable to cart items. There should be some discount codes that are only applicable to the whole cart.
5. Get the total price of a cart item
6. Get the total price of the whole cart
7. Get the list of the current cart items
- It should not return any cart items with zero quantity
- It should not return two cart items with the same product id

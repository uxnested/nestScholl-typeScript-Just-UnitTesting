# NestSchool-typeScript-Just-UnitTesting


## Module 1 Task
### Overview 
* What is presented in this document
* Keywords: TypeScript, Jest, Unit Testing
* Glossary:
* TypeScript: TypeScript is a strongly typed, object-oriented, compiled language.TypeScript is both a language and a set of tools. TypeScript is a typed superset of JavaScript compiled into JavaScript. In other words, TypeScript is JavaScript plus some additional features. readmore
* Unit Testing(Jest): Unit Testing is a type of software testing where individual units or components of the software are tested. The purpose is to validate that each unit of the software code performs as expected. read more
* Sourcetree(Optional): Sourcetree simplifies how you interact with your Git repositories so you can focus on coding. Visualize and manage your repositories through Sourcetree's simple Git GUI
#### What you will learn:
## Typescript and Unit Testing  
## Task 1
.
- Package-delivery services, such as FedEx, and DHL offer a number of different shipping options, each with specific costs associated. Create an inheritance hierarchy to represent various types of packages.

- Instruction:
1. Use class Package as the base class of the hierarchy, then include classes TwoDayPackage and OvernightPackage that derive from Package.
2. Base class Package should include data members representing the name, address, city, state, and ZIP code for both the sender and the recipient of the package, in addition to data members that store the weight (in ounces) and cost per ounce to ship the package.
3. Package’s constructor should initialize these data members. Ensure that the weight and cost per ounce contain positive values.
4. The package should provide a public member function calculating cost that returns a double indicating the cost associated with shipping the package. The package’s calculate cost function should determine the cost by multiplying the weight by the cost per ounce.
5. Derived class TwoDayPackage should inherit the functionality of the base class Package, but also include a data member that represents a flat fee that the shipping company charges for a two-day-delivery service.
6. twoDayPackage’s constructor should receive a value to initialize this data member. TwoDayPackage should redefine the member function calculateCost so that it computes the shipping cost by adding the flat fee to the weight-based cost calculated by base class Package’s calculateCost function.
7. Class OvernightPackage should inherit directly from class Package and contain an additional data member representing an additional fee per ounce charged for overnight delivery service. OvernightPackage should redefine the member function calculate cost so that it adds the additional fee per ounce to the standard cost per ounce before calculating the shipping cost.
8. Write a test program that creates objects of each type of Package and tests member function to calculate the cost. (i.e. Package package1,TwoDayPackage package2, OvernightPackage package3.
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



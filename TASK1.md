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
8. Write a test program that creates objects of each type of Package and tests member function to calculate the cost. (i.e. Package package1,TwoDayPackage package2, OvernightPackage package3.)
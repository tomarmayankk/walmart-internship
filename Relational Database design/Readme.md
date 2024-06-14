# Here is your task
Your task is to draft a UML class diagram describing the data processors for a pipeline. The component responsible for reading in input data is being designed by another engineer, so you only need to worry about what happens to the data when it reaches your processor. 

## You may assume three classes already exist:

1. Datapoint: this class represents both raw and processed data points. Any time data moves between methods you may use this class as an abstraction.
2. ModeIdentifier: an enum used to identify a processor mode.
3. DatabaseIdentifier: an enum used to identify a database connection.
 

## Your task is to draft an ERD for an appropriately normalized relational database that satisfies these requirements:

1. The database should store information related to the following products.
- Pet food, which has a name, manufacturer, weight, flavor, and target health condition.
- Pet toys, which have an associated material, name, manufacturer, and durability.
- Pet apparel, which has a color, manufacturer, size, name, and specific care instructions.
 
2. Each product should be associated with one or more animals.
 
3. Each product should be associated with a manufacturer.
 
4. The database should track customers and their transactions.
- It should store customer names and email addresses.
- Customers can make transactions to purchase one or more products.
- Each transaction should store the date and the products involved.
 
5. The database should track shipments to various Walmart locations.
- Each location should be represented by a name and a zip code.
- A shipment is recorded as an origin, a destination, and a collection of products, each with an associated quantity.
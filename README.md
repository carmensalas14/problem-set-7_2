# Problem Set 7.2 - Intro to Relational Databases

### Directions
For this problem set, you will be working with the [Pagila](https://github.com/devrimgunduz/pagila) database. 

## Part I: SQL Challenges 
1. What percentage of films have a rental rate of $0.99?
2. What is the percentage breakdown of all films by rating? 
3. Which actor appeared in the most films?
4. Which customer has the most movie rentals?
5. What was the longest rental period? (Hint: See `rental.rental_date` and `rental.return_date`)
6. What is the address of the store with the most films in their inventory?
7. Which category has the most films? How many films are in that category?
8. What is the address of the customer "Margaret Moore"? (Just the street address. Not the district, city, and ZIP code)
9. There is a customer with the email "CARMEN.OWENS@sakilacustomer.org". What is the name of the city that they live in?
10. What country is Store #2 (`store_id = 2`) located in?
11. What is the total replacement cost of each store's entire inventory?

## Part II: Entity Relationship Diagram
Create an Entity Relationship Diagram using [draw.io](https://draw.io). Include the following entities in your diagram.
* film
* actor
* category
* film
* language
* inventory
* rental
* staff
* store
* customer

#### Note
There are some M:M relationships in here. Be sure to include the cross reference tables that mediate these relationships. For example, there is a M:M relationship between `film`s and `actor`s. This relationship is mediated by the `film_actor` table. Be sure to include that in your ERD as well.

Lastly, for your entities, you do not have to list the data types next to your entities (column). Simply place an asterisks next to the primary key of the entity. See below:
![sample ERD]('./erd.png')


## Due Date
9AM on Monday, March 31


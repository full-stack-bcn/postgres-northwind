(Taken from [Homework 1 of CMU DB Course](https://15445.courses.cs.cmu.edu/fall2021/homework1/))

Questions:

1. List all category names ordered alphabetically.
2. Get all unique ``ShipNames`` from the ``order`` table that contain a hyphen (``-``).
3. Indicate if an order's ``ShipCountry`` is in North America (USA, Mexico or Canada)
4. For each ``Shipper``, find the percentage of orders which are late.
5. Get the number of products, average unit price (rounded to 2 decimal places), minimum unit price, maximum unit price, and total units on order for categories containing greater than 10 products. Order by Category ID.
6. For each of the 8 discontinued products in the database, which customer made the first ever order for the product? Output the customer's ``company_name`` and ``contact_name``.
7. For the first 10 orders by ``customer_id BLONP``: get the order's ``id``, date, previous date, and difference between the rpevious and current. Return results ordered by ``order_date`` (ascending).
8. For each ``customer``, get the ``company_name``, ``customer_id``, and "total expenditures". Output the bottom quartile of Customers, as measured by total expenditures.
9. Find the youngest employee serving each ``region``. If a region is not served by an employee, ignore it.
10. Concatenate the ``product_name``s ordered by the Company ``'Queen Cozinha'`` on ``2014-12-25``. Order the products by ``id`` (ascending). Print a single string containing all the dup names separated by commas like ``Mishi Kobe Niku, NuNuCa Nuß-Nougat-Creme...``.


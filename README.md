# Chalao-Ridesharing
Chalao is a fictitious ridesharing app that operates in Dhaka, Bangladesh. They need to find out the customers who registered on the platform on January 2021 and took at least one ride in May 2023. To find out these customers, first I created a Common Table Expression (CTE) that lists customers who registered on January 2021. Note, Chalao started its operation in the same month, January 2021.

Second, I created another CTE to find out the people with their trip time in May 2023. This time, I restricted it so it returns only the customers who registered on January 2021.

In the final step, I calculated the number of trips these people took in May 2023. I further used a join statement using the ID field to see all the information of these customers.

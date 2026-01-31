# Food Delivery Data Analysis – Innomatics Research Labs

## Objective
Merge transactional, user, and restaurant datasets to analyze order trends,
user behavior, revenue distribution, and membership impact.

## Datasets
- orders.csv (Transactional)
- users.json (User Master)
- restaurants.sql (Restaurant Master)

## Join Logic
- orders.user_id → users.user_id (LEFT JOIN)
- orders.restaurant_id → restaurants.restaurant_id (LEFT JOIN)

## Tools
Python, Pandas, NumPy, SQLite

## Output
final_food_delivery_dataset.csv

## Author
Vishal Tiwari

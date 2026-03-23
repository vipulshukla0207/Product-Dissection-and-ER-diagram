# Product-Dissection-and-ER-diagram
Product Dissection using Flipkart Data

-->Product Dissection: Flipkart

Company Overview: 
Flipkart was founded in October 2007 by Sachin Bansal and Binny Bansal. Initially launched as an online bookstore, Flipkart has grown into one of India’s leading e-commerce platforms.
Today, it offers a wide range of products including electronics, groceries, fashion, and daily essentials, making it an integral part of modern digital life. Its user-friendly interface and engaging features attract millions of daily users.

Real-World Problems Solved by Flipkart:

1. Access to Essential Goods

Problem: Limited availability of products, especially in rural areas.

Solution: Flipkart enables users to purchase a wide range of goods from a single platform and get them delivered to their doorstep.

2. Connecting Sellers & Customers

Problem: Limited reach of sellers and monopoly of local markets.

Solution: Flipkart connects sellers and buyers across India, allowing seamless trade between different regions.

3. Promotion of Local Products

Problem: Lack of visibility for regional and cultural products.

Solution: Flipkart provides a platform for local sellers to showcase and sell their products nationwide.

4. High Cost of Goods

Problem: Price manipulation by local sellers and lack of price transparency.

Solution: Flipkart offers competitive pricing, discounts, and deals to ensure affordability.

--> Key Features of Flipkart:

1- Doorstep Delivery – Convenient delivery to desired locations

2- Offers & Discounts – Attractive deals across categories

3- Multiple Categories – Electronics, Fashion, Grocery, etc.

4- Wishlist & Cart – Save items for future purchases

5-Pan-India Connectivity – Buyers and sellers across regions

6-Employment Generation – Opportunities for delivery partners

Case Study Summary:

Flipkart has transformed the Indian e-commerce ecosystem by:

1-Expanding access to goods in rural and urban areas

2-Empowering small and local businesses

3-Creating job opportunities

4-Enhancing customer convenience through technology

Despite challenges, Flipkart continues to innovate and remain competitive in the market.

Database Schema Design

This project includes a conceptual database schema representing Flipkart’s platform.

1- Users:

-user_id (PK)

-name

-email

-phone

2- Seller:

-seller_id (PK)

-name

-email

-phone

3-Category

-category_id (PK)

-name

-description

4-Product

-product_id (PK)

-seller_id (FK)

-category_id (FK)

-name

-price

-stock

-description

5-Product Rating

-rating_id (PK)

-product_id (FK)

-user_id (FK)

-review

-rating_date

6- Cart

-cart_id (PK)

-user_id (FK)

7- Cart Item

-cart_item_id (PK)

-cart_id (FK)

-product_id (FK)

-quantity

8- Wishlist

-wishlist_id (PK)

-user_id (FK)

-product_id (FK)

9-Discount

-discount_id (PK)

-discount_percentage

-description
10- Order

-order_id (PK)

-user_id (FK)

-product_id (FK)

-discount_id (FK)

11- Address

-address_id (PK)

-user_id (FK)

-order_id (FK)

-street

-city

-state

-pin_code

12- Payment

- payment_id (PK)
- order_id (FK)
- amount
- method
- status

Author

Vipul Shukla
Aspiring Data Analyst

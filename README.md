# IMS
A Python-based Inventory Management System with bulk operations, CSV imports, and sales tracking for efficient stock management.

Problem Statement

Many small to medium-sized businesses struggle with inefficient inventory management due to manual processes, leading to inaccurate stock levels, stockouts, overstocking, and challenges in tracking sales and revenue. The Inventory Management System (MIS) addresses this by providing a lightweight, automated solution to add, update, and monitor inventory, record sales, and generate insights like low-stock alerts and revenue reports, with support for bulk operations via CSV imports, all stored in simple text files for accessibility.

Approach

Built in Python with an object-oriented approach, the MIS uses a Product class for items and an Inventory class for logic, storing data in inventory.txt and sales.txt. It maintains an in-memory dictionary updated through user actions via a menu-driven interface, ensuring data persistence with file I/O, input validation to prevent errors, and scalability with bulk features like CSV stock updates. Key functions include load_inventory and save_inventory for file handling, record_bulk_sales and bulk_update_stock_from_csv for efficiency, and total_revenue_and_inventory_value using reduce for calculations, delivering a user-friendly tool for small businesses.

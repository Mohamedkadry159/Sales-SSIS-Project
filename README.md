This project focused on designing and implementing a Sales Data Mart using the AdventureWorks database, applying ETL best practices to transform and integrate data efficiently.

🔹 Key Techniques Used:
✅ Lookup Transformations – Used to join data from multiple tables, similar to a LEFT JOIN, with options to handle unmatched records. Also leveraged Lookup to retrieve Surrogate Keys (SKs) for fact table mapping.
✅ Slowly Changing Dimensions (SCD) – Implemented SCD Type 2 to track historical data, ensuring a complete record of changes over time by using Is_Current, Start_Date, and End_Date fields.
✅ Sales Data Mart Structure:

1️⃣Product Dimension – Integrated product details for better sales insights.

2️⃣Customer Dimension – Organized customer data for improved segmentation.

3️⃣Territory Dimension – Mapped geographical sales performance.

4️⃣Date Dimension – Extracted from an Excel sheet for enhanced time-based analysis.

❇Fact Table (Sales):
1️⃣Implemented Full Load for initial data population.
2️⃣Designed an Incremental Load process to efficiently update new and modified records.
✅Used Lookup transformations to retrieve Surrogate Keys (SKs) for dimension mapping.
✅ Data Type Conversion – Applied Data Conversion Transformation to ensure proper data type mapping, preventing errors in the ETL process.
✅ Sort Transformation – Used to remove duplicates and ensure properly ordered data before loading into the warehouse.
💡 Project Takeaways:
📌 Sales Data Mart enables optimized reporting and analytics.
📌 Storing historical data using Slowly Changing Dimensions (SCD Type 2) ensures accurate tracking of business changes.
📌 Implementing both Full & Incremental Loads enhances performance and data freshness.
📌 Using Lookup transformations for SK retrieval maintains referential integrity in fact tables.
📌 Data Type Conversion prevents compatibility issues across sources and destinations.
📌 Sort Transformation helps in deduplication and maintaining data integrity.

This Sales Data Mart project at ITI has been an incredible learning experience, strengthening my SSIS & data warehousing expertise. I’m excited to apply these skills to future challenges! If you're working with ETL pipelines, data warehouses, or SSIS, let’s connect and share insights! 🚀

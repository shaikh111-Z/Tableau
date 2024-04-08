
# Enhancing Manufacturing Efficiency Through Data-Driven Insights

![1-min-1](https://github.com/shaikh111-Z/Tableau/assets/83855661/35a11248-b5b2-4196-8ef0-7cab64a5eea6)


# Problem Statement
In the manufacturing landscape, efficiency, cost management, and employee performance are interconnected factors crucial for success. With access to datasets on manufacturing production and employee performance, the challenge is to leverage Tableau's capabilities to uncover insights that streamline processes, optimize resource allocation, and enhance productivity. The goal is to identify trends and patterns that enable informed decision-making to improve manufacturing operations and performance.

# Objective
The objective of this project is to utilize Tableau's advanced features to craft a compelling narrative from the provided datasets. This involves thorough data preparation, intelligent data modeling, and the skillful application of calculated fields and Tableau functions for sophisticated analysis. The ultimate goal is to construct an interactive and intuitive dashboard in Tableau that showcases key discoveries and offers concise, actionable insights into enhancing manufacturing operations and performance.

# Background
ProManu Analytics has been provided with two datasets: 'Manufacturing Production Data' and 'Employee Performance Metrics'. These datasets contain detailed information about products, production processes, workforce demographics, and employee performance ratings. The challenge is to explore these datasets to identify trends and insights that could streamline manufacturing processes, optimize resource allocation, and enhance employee productivity.

# Data Sources
ManufacturingDataset1.xlsx: Contains detailed information about production data, including product IDs, production dates, costs, quantities, and warehouse locations.      
ManufacturingDataset2.xlsx: Provides insights into employee performance metrics, covering employee IDs, departments, salaries, performance ratings, and countries of operation

# Attributes
The "ManufacturingDataset1.xlsx" file contains the following columns:

1. **ProductID**: A unique identifier for each product.  (Primary Key)
2. **ProductType**: The type of the product (e.g., Electronics, Furniture).
3. **ProductionDate**: The date when the product was manufactured.
4. **ProductionCost**: The cost of producing the product.
5. **CountryOfOrigin**: The country where the product was manufactured.
6. **QuantityProduced**: The quantity of the product produced.
7. **WarehouseLocation**: The location of the warehouse where the product is stored

The "ManufacturingDataset2.xlsx" file contains the following columns:

1. **EmployeeID**: A unique identifier for each employee.
2. **Department**: The department in which the employee works.
3. **HireDate**: The date when the employee was hired.
4. **Salary**: The salary of the employee.
5. **CountryOfOperation**: The country where the employee operates.
6. **ProductID**: A unique identifier for products, corresponding to 'ProductID' in "ManufacturingDataset1.xlsx".  (Foreign Key)
7. **PerformanceRating**: The performance rating of the employee (out of 10).
8. **Employee Training Record:** Training records for each employee.

# Part 1: Data Cleaning, Modeling, and Advanced Analysis in Tableau
- **Data Preparation**: Import datasets into Tableau, perform preliminary examination, and address any data quality issues or inconsistencies.
- **Hierarchies in Production Data**: Create hierarchies for 'ProductionDate', 'ProductType', and 'WarehouseLocation' to aid in data exploration.
- **Calculated Fields for Cost Analysis**: Determine cost per unit produced and analyze variations across different product types.
- **Grouping Employees and Salary Analysis**: Group employees by department, analyze salary distribution, and create salary bins for analysis.
- **Product Type Distribution and Employee Tenure Calculation**: Visualize product type distribution and calculate tenure of each employee.
- **Aggregate Functions and Top N Analysis**: Calculate average performance ratings and total salary expenditure by department, and identify top products with highest production costs.
- **Predictive Analysis and Cluster Analysis**: Use trend lines for predicting future salary trends and apply clustering to group employees based on performance and salary.
- **Market Basket Analysis**: Conduct market basket analysis to find associations between product types and warehouse locations, and create custom date parsing for production analysis.
- **Employee Training Analysis**: Create calculated fields to analyze employee training data and correlate it with performance ratings.

# Dashboard Building
- **Comprehensive Manufacturing Dashboard**: Created an interactive dashboard showcasing key metrics such as production costs, employee distribution, performance ratings, and product trends.

- **Dashboard Design and Functionality**: Focus on user-friendly design and functionality, ensuring the dashboard is visually appealing and provides interactive elements.

- **Time-Based Analysis and Interactive Employee Data**: Incorporated time-based analysis and created interactive sections for analyzing employee data.
  
- **Visualization of Production and Cost Data**: Implemented visualizations that effectively display production volumes and cost data.
  
- **Key Insights and Data Storytelling**: Provide a section summarizing key insights and stories from the data, highlighting significant findings or trends.

# Key Insights
- **Product Type Performance**: Determine the performance of different product types in terms of production costs, quantities produced, and warehouse locations to prioritize high-performing products.
- **Employee Performance Evaluation**: Analyze performance ratings and tenure of employees across departments to identify top-performing teams and areas for improvement.
- **Salary Distribution and Trends**: Explore salary distribution and trends within departments to ensure fair compensation and identify opportunities for salary optimization.
- **Country-wise Operations Analysis**: Understand the performance and contribution of employees operating in different countries to inform strategic decisions regarding international operations.
- **Departmental Performance Comparison**: Compare performance ratings and salary expenditure across departments to identify areas of excellence and potential inefficiencies.
- **Predictive Analysis for Future Trends**: Use predictive modeling to forecast future salary trends and production costs, enabling proactive decision-making and resource planning
- **Market Basket Analysis**: Identify associations between product types and warehouse locations to optimize inventory management and streamline logistics.
- **Training Impact on Performance**: Analyze the impact of employee training on performance ratings to guide investment in workforce development initiatives.

# Technical Summary
- This project involves analyzing manufacturing production and employee performance datasets using Tableau.
- The datasets are cleaned, modeled, and analyzed to derive key insights.
- Techniques such as hierarchies creation, calculated fields, dynamic filters, predictive modeling, and market basket analysis are employed to uncover trends and patterns.
- Insights include production efficiency, product performance, employee evaluation, salary distribution, international operations analysis, and predictive trends.
- The findings are visualized in an interactive dashboard, facilitating informed decision-making and optimization of manufacturing operations.

# Conclusion
In conclusion, the analysis of manufacturing production and employee performance datasets using Tableau has provided valuable insights for enhancing efficiency and productivity in the manufacturing industry. By uncovering trends and patterns in production, employee performance, and resource allocation, this project offers actionable recommendations for optimizing processes, improving performance, and driving strategic decision-making. The interactive dashboard serves as a powerful tool for stakeholders to visualize and understand key metrics, facilitating continuous improvement and innovation in manufacturing operations.These insights collectively contribute to enhancing manufacturing efficiency, optimizing resource allocation, and improving overall performance in the manufacturing industry.

Below are glimpses of the dashboard highlighting key metrics and findings.

![T1](https://github.com/shaikh111-Z/Tableau/assets/83855661/757782a7-6a9d-4197-88ce-fe3e7302df8a)

![T2](https://github.com/shaikh111-Z/Tableau/assets/83855661/802e0576-b1b1-4ab7-b4f7-ce8b1ede5092)







# Gravity-Bookstore-
Building a Data Warehouse Model with Microsoft ETL for Power BI Analysis

## Project Description
The Gravity Bookstore project aims to design and implement a comprehensive data solution for capturing, analyzing, and visualizing crucial information regarding books, customers, and sales transactions.
###  key components:
1)Data Warehouse Construction:
  *Design and implement a robust data warehouse architecture to effectively store and manage data pertaining to books, customers, 
    and orders.
  *Utilize Microsoft ETL (Extract, Transform, Load) tools for seamless data integration from various sources into the data 
    warehouse.

2)Data Cubes Development:
  *Develop data cubes tailored for analyzing sales orders and customer data, enabling multidimensional analysis and insights 
    generation.
  *Utilize OLAP (Online Analytical Processing) techniques to facilitate efficient querying and exploration of the data.

3)Dashboard Development:
  *Design and implement an intuitive dashboard interface for easy access and visualization of key business metrics and 
     performance indicators.
  *Leverage Power BI, a powerful data visualization tool, to create interactive and visually compelling dashboards that provide 
     actionable insights.


The project commenced with the construction of a data warehouse using SQL Server and employed SQL Server Integration Services (SSIS) for structured data gathering, effectively organizing data related to books, customers, and sales. Subsequently, data cubes were crafted utilizing SQL Server Analysis Services (SSAS) in tabular mode, facilitating in-depth analysis of order patterns and customer interactions. Lastly, a user-friendly Power BI dashboard was developed, seamlessly integrating insights gleaned from the data warehouse and cubes to facilitate effortless monitoring and enhancement of business performance.


## Building Data Warehouse
The database has a complex structure with many related tables, including many-to-many relationships,
A galaxy schema allows for a higher level of normalization And Manage Relationships between 2 Fact table , which can help in reducing data redundancy and ensuring data consistency.

![Glaxay Schema ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/Galaxy%20Schema%20.PNG?raw=true)


## ETL using SSIS
SQL Server Integration Services (SSIS) was utilized for Extract, Transform, Load (ETL) processes to populate the warehouse with data. This approach ensured systematic collection and organization of information regarding books, customers, and sales within the data warehouse.

 ### Table Facts
   ![Accumualitive Order ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/ACCUMULATIVE%20FACT.PNG?raw=true)

   ![ Fact Sales ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/FACT_SALES.PNG?raw=true)

 ### Table Dimantions 
   ![Book_Dim](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/DIM_BOOK.PNG?raw=true)
   
   ![Adress_Dim ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/DIM_ADDRESS.PNG?raw=true)
   
   ![Shipping_Dim ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/DIM_SHIPPING.PNG?raw=true)
   
   ![Customer_Dim ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/DIM_CUSTOMER.PNG?raw=true)
   
   ![Book_Author_Dim ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/BOOK_AUTHOR.PNG?raw=true)



## SSAS
Within the data cubes, perspectives, calculations, and Key Performance Indicators (KPIs) were integrated to enrich the analytical capabilities. Perspectives were employed to offer different viewpoints on the data, facilitating varied analyses tailored to specific business requirements. Calculations were implemented to derive new measures or modify existing ones, enabling deeper insights into the dataset. Additionally, Key Performance Indicators (KPIs) were defined to gauge the performance of the business against predefined targets, providing actionable insights for strategic decision-making.

  ![Cube for fact sales  ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/cube2.PNG?raw=true)

  ![Cube for accumualitive  order  ](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/cube1.PNG?raw=true)




  ## Dashboard with Power BI

 

  ![Summary](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/page1.PNG?raw=true)
  
  ![Book](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/Page2.PNG?raw=true)
  
  ![Customer](https://github.com/Hadikhaled/Gravity-Bookstore-/blob/main/Snapshots/Page3.PNG?raw=true)
  








     

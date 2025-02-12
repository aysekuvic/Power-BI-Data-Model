Power BI Data Model

 Overview

This project focuses on designing an efficient star schema data model for chocolate sales analysis. The data model supports revenue tracking across different geographic regions and enables insightful business analytics in Power BI.

 Data Model Structure

The project follows a star schema design with a central fact table (shipments) connected to multiple dimension tables:

Fact Table: shipments (contains revenue-related data)

Dimension Tables:

calendar (date details such as month and weekday names)

products (product categories and cost per box)

locations (geographical data such as region and country)

people (sales personnel details)

This structure enhances query performance and ensures seamless data analysis.

Key Features

Optimized Star Schema: Well-structured relationships between fact and dimension tables.

Scalability: Supports business growth with a flexible and expandable model.

Efficient Queries: Improves Power BI performance and reporting capabilities.

Data Integrity: Ensures accurate and consistent data through well-defined relationships.

Setup & Installation

Clone this repository:

git clone https://github.com/aysekuvicpowerbi-data-model.git

Open Power BI Desktop.

Load the .pbix file from the pbix/ folder.

Explore the data model and validate relationships.


Author: Ayse Karasu

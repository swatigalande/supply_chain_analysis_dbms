# supply_chain_analysis_dbms

Objective / Abstract

The supply Chain is the network of production and logistics involved in producing and delivering goods to customers. And Supply Chain Analysis means analyzing various components of a Supply Chain to understand how to improve the effectiveness of the Supply Chain to create more value for customers.

Key objectives include:

Each of these supply chain analytics can increase the overall efficiency of business operations, which can lead to sizable cost savings.
Descriptive Analytics focuses on understanding what happened in the past by analyzing historical data. It can provide insights on key performance metrics, such as inventory levels, lead times, and delivery performance. Descriptive analytics can help identify patterns and trends in past supply chain operations, allowing organizations to make informed decisions about future strategies.

Diagnostic Analytics goes beyond descriptive analytics by identifying the root causes of supply chain issues. By analyzing data from different sources, such as suppliers, logistics providers, and customers, organizations can identify the factors that contribute to delays, disruptions, or quality issues in their supply chain.
Here is a dataset we collected from a Fashion and Beauty startup. The dataset is based on the supply chain of Makeup products. Below are all the features in the dataset:

Product Type
SKU
Price
Availability
Number of products sold
Revenue generated
Customer demographics
Stock levels
Lead times
Order quantities
Shipping times

Technologies Used
Python: For data analysis, cleaning, and visualization.
SQL (MySQL Workbench): For database management and integration.
Pandas: For data manipulation and preprocessing.
Matplotlib, Seaborn: For creating visualizations.
Jupyter Notebook: For exploratory data analysis.
OS Module: For handling file paths dynamically.
SQL Integration
The project integrates with MySQL to store and query the dataset. The following steps were performed:

The supply_chain_datasets.csv was processed using Python and imported into a MySQL database (supply_chain_anlysis) with a table named supply_chain.
Table creation and data insertion were automated by dynamically mapping column data types.
This integration enables efficient querying and further analysis of the dataset.
How to Use


. Install required Python libraries: pip install -r requirements.txt

.Set up the MySQL database: Create a database named global_suicide_rate. Use the provided Python script to import the dataset into the suicide_data table.

.Run the Jupyter Notebook: ** jupyter notebook GLOBAL_SUICIDE_RATE_ANALYSIS(1986-2016).ipynb


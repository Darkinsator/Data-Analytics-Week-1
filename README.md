# Data-Analytics-Week-1
Data-Analytics-Week-1


# Chapter 1: The Data Analyst

# What is Data analytics?
Data analytics is basically the science and techniques of analysing raw data to make conclusions about information.
Data analytics has many processes and techniques that have already been automated into mechanical processes  and algorithms that work over raw data for human consumption.
Data analytics can be used by a wide number  of entites such as businesses, to increase the overall performance therefore maximizing  their project

Analysts working with data move through a series of different steps as they seek to gain business value from their organization's data.
Analysts move through a process as they acquire new data, clean and manipulate that data, analyze it, create visualizations, and then report and communicate their results to business leaders.
These processes are:
1. Data Acquisition
2. Cleaning and Manipulation
3. Analysis
4. Visualization
5. Reporting and Communication

![fig1](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/d74bf5d0-24c8-40a4-ac14-83c0a51281ce)

# Roles of a data anaylst
1. Data collection a preparation
2. Data Analysis
3. Data Visualization and Storytelling
4. Decision Support - Making recommendations based on data-driven insights to help guide business decisions, providing context around the data, including potential implications and future trends.
5. Collaboration and Communication:
6. Continuous Learning and Adaptation:

Analytical Techniques
Analysts use a variety of techniques to draw conclusions from the data at their disposal. To help you understand the purpose of different types of analysis, we often group these techniques into categories based on the purpose of the analysis and/or the nature of the tool. Let's take a look at the major categories of analytics techniques.

Descriptive Analytics
Predictive Analytics
Prescriptive Analytics

Machine Learning, Artificial Intelligence, and Deep Learning
Algorithms are used in machine learning to extract knowledge from your datasets that you may utilize to inform future decisions. This is true irrespective of the particular field in which you operate, as machine learning finds application in a wide range of domains. 

Analytics Tools
Software helps analysts work through each one of the phases of the analytics process. These tools automate much of the heavy lifting of data analysis, improving the analyst's ability to acquire, clean, manipulate, visualize, and analyze data. They also provide invaluable assistance in reporting and communicating results.

![FIGURE_1 7_Data_analysis_in_Microsoft_Excel](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/5c828598-29dd-4581-96fb-9cd6645621a8)
Data analysis in Microsoft Excel
![FIGURE_1 8_Data_analysis_in_RStudio](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/611730f3-1eaa-44c8-9a52-c3d75fb33ad6)
Data analysis in RStudio


# Chapter 2: Understanding Data

Data structure is an important factor in understanding how data works.

Data types is also important as it defines what catagory data goes into and also helps with data analysis. 

![FIGURE_2 1_Person_Data](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/802a7818-113f-44af-af7b-d25245278b8e)

Person Data

Let's explore some of the most common data types that give structured data its structure.

Character: The character data type limits data entries to allow only allow valid characters.Depending on your needs, multiple data types are available that can enforce character limits.

Alphanumeric: The most widely used data type for storing character data. Data element contains both numbers and letters. For example To accurately represent a given street address, both the house number and the street name are required.

Each database software has its unique method of implementing character data types to handle the nuances related to character data. The most significant difference has to do with how much data a particular data element can contain.

# Unstructured Data Types
While much of the data we use to record transactions is highly structured, most of the world's data is unstructured. Unstructured data is any type of data that does not fit neatly into the tabular model. 

# Categories of data

Quantitative vs. Qualitative Data
Quantitative data consists of numeric values.
Qualitative data consists of frequent text values.

Discrete vs. Continuous Data
Numeric data comes in two different forms: discrete and continuous.
Instead of counting, when you measure things like height and weight, you are collecting continuous data.
While whole numbers represent discrete data, continuous data typically need a decimal point.
Another way to think about it is that discrete data is useful when you have things you want to count
Instead of counting, when you measure things like height and weight, you are collecting continuous data. 

Categorical Data
In addition to quantitative, numeric data, there is categorical data. Text data with a known, finite number of categories is categorical.

Dimensional Data
Dimensional modeling is an approach to arranging data to facilitate analysis. Dimensional modeling organizes data into fact tables and dimension tables.
Fact tables store measurement data that is of interest to a business.
A table holding appointment data would be called a fact table.
Dimensions are tables that contain data about the fact. For appointment data, the veterinarian's office manager may want to understand who was at an appointment and if any procedures were performed.

![FIGURE_2 18_Dimension_illustration](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/db99cf66-080a-4112-af30-d26445e3b32b)

# Common Data Structures

In order to facilitate analysis, data needs to be stored in a consistent, organized manner. When considering structured data, several concepts and standards inform how to organize data.

Structured Data
Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows.

Unstructured Data
Unstructured data is qualitative, describing the characteristics of an event or an object. Images, phrases, audio or video recordings, and descriptive text are all examples of unstructured data.

Semi-Structured Data
Semi-structured data is data that has structure and that is not tabular. Email is a well-known example of semi-structured data. Every email message has structural components, including recipient, sender, subject, date, and time. However, the body of an email is unstructured text, while attachments could be anything type of file.

Text Files
Text files are one of the most commonly used data file formats. As the name implies, they consist of plain text and are limited in scope to alphanumeric data. One of the reasons text files are so widely adopted is their ability to be opened regardless of platform or operating system without needing a proprietary piece of software. Whether you are using a Microsoft Windows desktop, an Apple MacBook, or a Linux server, you can easily open a text file. Text files are also commonly referred to as flat files.

A unique character known as a delimiter facilitates transmitting structured data via a text file. The delimiter is the character that separates individual fields. A delimiter can be any character. Over the years, the comma and tab grew into a widely accepted standard. Various software packages support reading and writing delimited files using the comma and the tab. In addition, many coding languages have libraries that make it easy to write comma- or tab-delimited files. When a file is comma-delimited, it is known as a comma-separated values (CSV) file. Similarly, when a file is tab-delimited, it is called a tab-separated values (TSV) file.

JavaScript Object Notation
JavaScript Object Notation (JSON) is an open standard file format, designed to add structure to a text file without incurring significant overhead. One of its design principles is that JSON is easily readable by people and easily parsed by modern programming languages. Languages such as Python, R, and Go have libraries containing functions that facilitate reading and writing JSON files.

Consider Figure 2.29, which illustrates data about the first three pets from Table 2.1, formatted as JSON. As a person, it is easy to see that the information corresponding to an individual pet is within curly braces, with name-value pairs corresponding to the data elements and values.

![image](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/9158cb15-fce7-41e0-ae98-ed4ac91d4ec5)

Extensible Markup Language (XML)
Extensible Markup Language (XML) is a markup language that facilitates structuring data in a text file. While conceptually similar to JSON, XML incurs more overhead because it makes extensive use of tags. Tags describe a data element and enclose each value for each data element. While these tags help readability, they add a significant amount of overhead.

HyperText Markup Language (HTML)
HyperText Markup Language (HTML) is a markup language for documents designed to be displayed in a web browser. HTML pages serve as the foundation for how people interact with the World Wide Web. Similar to XML, HTML is a tag-based language. Figure 2.33 illustrates the creation of a table in HTML containing the data for a single pet. 

![image](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/7483a9a3-22fa-4964-852c-19daf4e7c410)


# Module 2: Data Preparation and Exploration

Chapter 3: Databases and Data Acquisition
The vast majority of transactional systems generate structured data, and we need technology that will help us store all of that data.
Exploring Databases

There are many different database options to choose from when an organization needs to store data. While many database products exist, they belong in one of two categories: 

Relational
Nonrelational

Database use cases

Online Transactional Processing
OLTP systems handle the transactions we encounter every day. Example transactions include booking a flight reservation, ordering something online, or executing a stock trade. While the number of transactions a system handles on a given day can be very high, individual transactions process small amounts of data. OLTP systems balance the ability to write and read data efficiently.

Normalization

Normalization is a process for structuring a database in a way that minimizes duplication of data. 

First normal form (1NF) is when every row in a table is unique and every column contains a unique value. Consider Figure 3.15, where there are separate rows for Giacomo and Eleonora. While Giacomo and Eleonora have the same home address, appending Eleonora's name in the Person_Name column to Giacomo's in the first row would violate 1NF. However, since each row is unique, Figure 3.15 is in 1NF.

![image](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/cc3611df-d456-4765-9e37-29ea237a2ada)

Second normal form (2NF) starts where 1NF leaves off. In addition to each row being unique, 2NF applies an additional rule stating that all nonprimary key values must depend on the entire primary key. To get to 2NF, the table from Figure 3.15 evolves into the tables in Figure 3.16. Note that the Person_Address table has a composite primary key composed of Person_ID and Addr_ID. The values of both Addr_Code and Addr_Desc are associated with the composite primary key.

Suppose Eleonora starts working from home and updates the Addr_Desc for her row with the value “Work.” That causes data corruption, as the Addr_Code corresponds to the Addr_Desc. Addr_Desc depends on Addr_Code, and with that change, “H” would mean both “Home” and “Work”.

![image](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/c1aa9b5b-0fda-4a16-9f36-34d7f6ec2708)

Third normal form (3NF) builds upon 2NF by adding a rule stating all columns must depend on only the primary key. Evolving Figure 3.16 into 3NF results in Figure 3.17. If Eleonora starts working from home, the only value that needs to change is Addr_Code in the Person_Address table. The description for each type of address is in the Addr_Code table. Similarly, the description for each state code is in the State_Code table. The result is that there is little redundancy in the data's storage location and that keys enforce the relationships between tables. Databases in 3NF are said to be highly normalized.


![image](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/80f6657c-b401-4d1c-82be-c8d769476bb8)

Online Analytical Processing
OLAP systems focus on the ability of organizations to analyze data. While OLAP and OLTP databases can both use relational database technology, their structures are fundamentally different. OLTP databases need to balance transactional read and write performance, resulting in a highly normalized design. Typically, OLTP databases are in 3NF.

On the other hand, databases that power OLAP systems have a denormalized design. Instead of having data distributed across multiple tables, denormalization results in wider tables than those found in an OLTP database. It is more efficient for analytical queries to read large amounts of data for a single table instead of incurring the cost of joining multiple tables together.

Data Acquisition Concepts

To perform analytics, you need data. Data can come from internal systems you operate, or you can obtain it from third-party sources. Regardless of where data originates, you need to get data before analyzing it to derive additional value. In this section, we explore methods for integrating data from systems you own. We also explore strategies for collecting data from external systems.

Data from transactional systems flow into data warehouses and data marts for analysis. Recall that OLTP and OLAP databases have different internal structures. You need to retrieve, reshape, and insert data to move data between operational and analytical environments. You can use a variety of methods to transfer data efficiently and effectively.

One approach is known as extract, transform, and load (ETL). As the name implies, this method consists of three phases:

Extract:  In the first phase, you extract data from the source system and place it in a staging area. The goal of the extract phase is to move data from a relational database into a flat file as quickly as possible.
Transform:  The second phase transforms the data. The goal is to reformat the data from its transactional structure to the data warehouse's analytical design.
Load:  The purpose of the load phase is to ensure data gets into the analytical system as quickly as possible.
Extract, load, and transform (ELT) is a variant of ETL. With ELT, data is extracted from a source database and loaded directly into the data warehouse. Once the extract and load phases are complete, the transformation phase gets underway. One key difference between ETL and ELT is the technical component performing the transformation. With ETL, the data transformation takes place external to a relational database, using a programming language like Python. ELT uses SQL and the power of a relational database to reformat the data.

ETL Vendors

Whether you choose ETL or ELT for loading your data warehouse, you don't have to write transformations by hand. Many products support both ETL and ELT. Before you pick one, carefully evaluate the available free and paid options to determine the one that best fits your needs and system architecture goals.

An initial load occurs the first time data is put into a data warehouse. After that initial load, each additional load is a delta load, also known as an incremental load. A delta load only moves changes between systems. Figure 3.23 illustrates a data warehouse that launches in January and uses a monthly delta load cycle. The initial load happens right before the data warehouse becomes available for use. All of the transactional data from January becomes the delta load that initiates on the first of February. Figure 3.23 illustrates a monthly delta-load approach that continues throughout the year.


![image](https://github.com/Darkinsator/Data-Analytics-Week-1/assets/112648301/54ab60ea-db8b-4d21-a4e1-582c60c7a7f6)

long your batch window is, think carefully about moving current data into the data warehouse without losing history.

Data Collection Methods
Augmenting data from your transactional systems with external data is an excellent way to improve the analytical capabilities of your organization. For example, suppose you operate a national motorcycle rental fleet and want to determine if you need to rebalance your fleet across your existing locations. You also want to evaluate whether it is profitable to expand to a new geographic region, as well as predict the best time and place to add motorcycles to your fleet.

Application Programming Interfaces (APIs)
1. Web Services
2. Web Scraping
3. Human-in-the-Loop
4. Surveys
5. Survey Tools
6. Observation
7. Sampling

Working with Data

Data Manipulation
When manipulating data, one of four possible actions occurs:

Create new data.
Read existing data.
Update existing data.
Delete existing data.
The acronym CRUD (Create, Read, Update, Delete) is a handy way to remember these four operations.

SQL uses verbs to identify the type of activity a specific statement performs. For each CRUD activity, there is a corresponding DML verb, as Table 3.8 illustrates. These verbs are known as keywords or words that are part of the SQL language itself.


SQL Example:

Select Animal_Name, Breed_Name from Animal

The previous query returns the same results as this query:

SELECT Animal_Name, Breed_Name FROM Animal

SQL can also span multiple lines. For example, rewriting the previous query as follows will return identical results:

SELECT Animal_Name, Breed_Name

FROM  Animal

Sorting;

SELECT  Animal_Name, Breed_Name

FROM   Animal

WHERE  Animal_Type = 'Dog'

AND   Weight> 60

ORDER BY Date_of_Birth ASC

If you want to return the youngest dog first, you change the ORDER BY clause as follows:

SELECT  Animal_Name, Breed_Name

FROM   Animal

WHERE  Animal_Type = 'Dog'

AND   Weight> 60

ORDER BY Date_of_Birth DESC

The ASC keyword at the end of the ORDER BY clause sorts in ascending order whereas using DESC with ORDER BY sorts in descending order. If you are sorting on multiple columns, you can use both ascending and descending as appropriate. Both the ASC and DESC keywords work across various data types, including date, alphanumeric, and numeric.


Exam Prep:

1. Describe the characteristics of OLTP and OLAP systems. 

The two main categories of relational databases are transactional (OLTP) and analytical (OLAP). Transactional systems use highly normalized schema design, which allows for database reads and writes to perform well. Analytical systems are denormalized and commonly have a star or snowflake schema. Remember that a star design simplifies queries by having a main fact table surrounded by dimensions. A snowflake design is more normalized than a star. While this approach reduces storage requirements, the queries are more complex than in a star schema.

2. Describe approaches for handling dimensionality. 

It is crucial to keep track of how data changes over time to perform historical analysis. Although an effective date approach is valid, the SQL queries to retrieve a value at a specific point in time are complex. A table design that adds start date and end date columns allows for more straightforward queries. Enhancing the design with a current flag column makes analytical queries even easier to write.

3. Understand integration and how to populate a data warehouse. 

The more data an organization has, the more impactful the analysis it can conduct. The extract, transform, and load (ETL) process copies data from transactional to analytical databases. Suppose an organization wants to use the power of a relational database to reformat the data for analytical purposes. In that case, the order changes to extract, load, and transform. Regardless of the approach, remember that a delta load migrates only changed data.

4. Differentiate between data collection methods. 

Data can come from a variety of sources. An organization may scrape websites or use publicly available databases to augment its data. While web scraping may be the only way to retrieve data, it is better if a published application programming interface exists. An API is more reliable since its structure makes for a consistent interface. If you want to capture the voice of the customer, a survey is a sound approach. Collecting data through observation is a great way to validate business processes and collect quantitative data.

5. Describe how to manipulate data and optimize queries. 

Analytical databases store massive amounts of data. Manipulating the entire dataset for analysis is frequently infeasible. To efficiently analyze data, understand that SQL has the power to filter, sort, and aggregate data. When focusing on a particular subject, creating a subset is an ideal approach. Although it is possible to create permanent tables to house subsets, using a temporary table as part of a query is viable for ad hoc analysis. When an analytical query performs poorly, use its execution plan to understand the root cause. It is wise to work with a database administrator to understand the execution plan and ensure that indexes exist where they are needed.















































Chapter 4: Data Quality



Chapter 5: Data Analysis and Statistics

















































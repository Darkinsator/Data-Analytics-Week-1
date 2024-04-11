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





































Chapter 4: Data Quality



Chapter 5: Data Analysis and Statistics

















































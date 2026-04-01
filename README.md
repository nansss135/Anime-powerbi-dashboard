 Anime Data Analysis Dashboard (Power BI)
 
 Project Overview
This project is a data transformation and visualization project built using Power BI. The goal is to simulate a real-world data engineering workflow by cleaning raw data using Power Query and creating an interactive dashboard to extract meaningful insights.
The dataset contains information about various anime including:
Title
Episodes
Ratings
Members (popularity)
Release details

 Objectives:
Clean and transform raw dataset using Power Query Editor
Extract meaningful columns from unstructured text data
Convert data into proper formats for analysis
Build an interactive Power BI dashboard
Visualize trends and insights from anime data

 Tools & Technologies Used
Power BI Desktop
Power Query Editor
Data Cleaning Techniques
DAX (Basic Measures)
Data Visualization

 Dataset Description:
The dataset initially contained messy, unstructured text such as:
Combined fields (Title + Type + Episodes + Dates + Members)
Numbers with commas (e.g., 3,218,472)
Mixed text and numeric values

After Cleaning:
The dataset was transformed into structured columns:
Title
Type (TV, Movie, etc.)
Episodes
Release Year
Members
Ratings

 Data Cleaning Process (Power Query)
Step 1: Load Data
Imported dataset into Power BI
Opened Power Query Editor
Step 2: Duplicate Column
Duplicated the Title column to extract multiple attributes
Step 3: Extract Information

Used:
Split Column by Delimiter
Extracted:
Episodes
Dates
Members
Step 4: Clean Numeric Data
Removed commas from numbers
Converted text to Whole Number
Step 5: Data Formatting
Changed data types:
Episodes → Number
Members → Number
Ratings → Decimal
Step 6: Remove Unnecessary Data
Deleted unwanted columns
Renamed columns properly

Dashboard Features
The dashboard includes:

 KPI Cards
Total Anime Count
Average Rating
Total Members
Total Episodes

 Visualizations
 Pie Chart → Distribution by Anime Type
 Bar Chart → Top Anime by Members
 Column Chart → Episodes comparison
 Table View → Detailed dataset

 Key Insights
Popular anime have significantly higher member counts
TV series dominate over movies in quantity
High-rated anime often correlate with high popularity
Episode count varies widely across genres

 How to Use This Project
Download the .pbix file
Open it in Power BI Desktop
Go to:
Power Query → View transformations
Report View → Explore dashboard
Interact with filters and visuals

Repository Structure
Anime-Data-Analysis
Anime.pbix
README.md
Future Improvements
Add slicers (Genre, Year)
Use advanced DAX measures
Integrate real-time API data
Improve UI/UX design of dashboard
 Author

Nandini Rajput
B.Tech CSE Student | Data Enthusiast



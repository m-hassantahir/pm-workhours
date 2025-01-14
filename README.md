# pm-workhours
Power BI Dashboards for Project Performance and Work Hours Analysis

PROJECT DESCRIPTION:

The client sought a solution to effectively track project performance and manage working hours, specifically focusing on monitoring estimated versus actual hours with dynamic filtering for detailed analysis. The project data, managed in Primavera and Excel, was provided in a wide-format Excel workbook. My role was to design and implement interactive Power BI dashboards that could showcase performance scenarios and be easily updated weekly with revised data.![image](https://github.com/user-attachments/assets/6ba62266-3f7c-43bb-be61-8be30071c409)

STEP BY STEP PROCESS

To prepare the wide-format data for Power BI, two approaches were explored:
1.	Unpivoting Data: The wide-format data was converted into a long-format structure using Power Query, with each row representing a date, task/phase, and its value. This transformation enabled the creation of dynamic visualizations like line charts for tracking progress and matrix tables for comparing planned versus actual metrics. Filters, slicers, and calculated measures were added for detailed performance analysis.
2.	Transposing Data: Another method involved dividing the Excel data into smaller logical tables by tasks or phases, transposing the data to have dates in rows and values in columns, and cleaning it for consistency. These tables were linked using the dates column as a primary key, enabling seamless analysis.

![image](https://github.com/user-attachments/assets/e08fb521-00f4-4de7-b3c1-7b9738b7842e)


To optimize the model further, I implemented a normalization approach by dividing the main data table (containing 376 employees) into three smaller tables to eliminate repeating values. Repeating fields such as area codes, company names, job titles, employee details, and work descriptions were moved into separate tables with unique values, reducing redundancy and improving performance. A unique date table was also created and linked to other tables to ensure consistency.
Two dashboards were developed to meet the client’s requirements:
1.	Line and Clustered Column Chart Dashboard: This dashboard showcased the project’s overall S-curve. The x-axis represented dates, while the clustered column y-axis displayed variables such as "Early Period % Planned (Target)," "Period % Earned," and "Period % Forecast." The line y-axis included "Early Cumulative % Planned (Target)," "Late Cumulative % Planned (Target)," "Cumulative % Earned," and "Cumulative % Forecast." A date slicer allowed users to filter data dynamically.
![image](https://github.com/user-attachments/assets/7ad5d6bc-b409-49f8-b6cf-62e8b0d79ea2)


  
3.	Work Hours and Employee Analysis Dashboard: This dashboard included a line chart showing dates on the x-axis and the sum of hours on the y-axis. Additional cards displayed the number of employees in a category and their average sell rate. Three slicers were included for enhanced interactivity: one for company (four companies in total), one for the scope of work, and one for dates (with year, quarter, and month filters).
![image](https://github.com/user-attachments/assets/812ca6d4-7150-452a-9b8d-f898956904d3)



These user-friendly dashboards enabled the client to monitor project performance, analyze working hours, and explore various scenarios efficiently, while providing an optimized and scalable solution for weekly updates.

FEATURES AND SKILLS DEMONSTRATED IN THE PROJECT 

A.  Data Transformation and Preparation:
1.  Converted wide-format data into long-format using Power Query's Unpivot Columns feature for better compatibility with Power BI.
2.  Transposed data to rearrange rows and columns, ensuring dates were in rows and values in columns for analysis.\
3.  Cleaned and optimized data by removing duplicates, inconsistencies, and unnecessary fields.
4.  Normalized the dataset by splitting the main table into smaller tables, extracting unique values for fields like employee details, work descriptions, and dates to improve performance and scalability.

B. Data Modeling and Relationships:
1.  Created logical relationships between tables using the dates column as a primary key to enable seamless integration across datasets.
2.  Designed an efficient data model by linking smaller tables (e.g., employee details, task categories, and dates) for better performance and easier management.

C.  Power BI Dashboard Development:
1.  Designed interactive dashboards tailored to the client’s requirements with user-friendly features and real-time insights.
2.  Implemented a Line and Clustered Column Chart for visualizing the project’s S-curve, showcasing planned, earned, and forecast metrics dynamically.
3.  Developed a line chart to display working hours over time, complemented by cards for displaying KPIs like the number of employees and their average sell rate.

D.  Dynamic Filtering and Slicers:
1.  Incorporated slicers for filtering data by company, scope of work, and dates, enabling users to analyze performance across various scenarios (e.g., year, quarter, or month).
2.  Added interactive features to allow users to drill down into detailed project metrics.

E.Technical Optimization:
1.  Reduced redundancy and improved performance by normalizing the data and creating unique value tables for fields with repeating entries.
2.  Ensured dashboards could be updated weekly with minimal effort by structuring the data model for easy integration of new Excel data.

F. Visualization and Analysis:
1.  Created visually appealing and intuitive dashboards that effectively communicated project performance metrics and working hour trends.
2.  Used calculated measures and metrics to track and compare cumulative planned, earned, and forecast percentages dynamically.


SKILLS HIGHLIGHTED

1.  Power BI Expertise: Dashboard creation, data visualization, Power Query, and advanced filtering.
2.  Data Modeling: Normalization, relationship building, and optimization.
3.  Data Transformation: Unpivoting, transposing, and cleaning data for analysis.
4.  Project Management Analysis: Ability to track and compare project metrics like planned vs. actual working hours.
5.  Problem Solving: Devised multiple solutions to handle wide-format data and optimize performance for large datasets.
6.  Communication: Designed dashboards with clear, actionable insights tailored to the client’s needs.

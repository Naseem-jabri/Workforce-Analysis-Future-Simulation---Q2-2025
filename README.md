Project Concept
This project provides a comprehensive analytical view of the Saudi labor market for the second quarter of 2025. It transitions from traditional descriptive reporting to Prescriptive Analytics by allowing decision-makers to simulate future growth scenarios and nationalization (Saudization) targets.

- The Problem & Purpose
The Problem: Stakeholders often struggle to visualize the immediate impact of policy changes (like increased Saudization) on total workforce numbers using static data.

Why it was Built: To bridge the gap between historical data and future planning, providing a tool that calculates real-time "What-if" scenarios for the Saudi workforce.

- Tools & Technologies
Power BI Desktop: For advanced data visualization and UI/UX design.

DAX (Data Analysis Expressions): To build complex measures for growth simulation and workforce distribution.

SQL (PostgreSQL/SQL Server): Used for the ETL process and building the Data Warehouse (DWH) foundation.

Excel: The primary source for the Q2-2025 raw dataset.

- Applied Learning Paths - Skills
ETL & Data Cleaning: Handling missing values and filtering out administrative totals (Grand Totals) to ensure data integrity.

DAX Modeling: Creating dynamic measures for Total Workforce, Expat Percentages, and Predicted Growth.

What-if Analysis (ML Simulation): Implementing Numeric Range Parameters to simulate future Saudi workforce increases.

UI/UX Design: Applying the F-Pattern layout, custom color palettes (#63458A), and rounded-border visuals for a modern executive look.

- How it Works
Exploration: Users can filter data by Age Group to see specific workforce distributions.

Simulation: Use the "The proposed Saudi increase" slider to adjust the expected growth percentage.

Real-time Results: The "Predicted Saudis" card updates instantly to show the target number of employees based on the selected growth rate.

- How to Run the Project
Download the .pbix file from this repository.

Ensure you have Power BI Desktop installed.

Open the file to interact with the dashboard and simulation sliders.

Name: Vaishnavi Deoaro Sonkusare 
Company: CODTECH IT SOLUTIONS 
ID: CT08DG1674 
Domain: Python Programming 
Duration: June to August 2025 
Mentor: NEELA SANTOSH KUMAR

##Overview of Project
Project Title: Automated Internship Performance Report Generator

Objective:
The project automates the process of reading students’ internship performance data from a CSV file, analyzing their scores, and generating a professional PDF certificate/report containing both individual results and statistical summaries.

Workflow Overview:

Read Data from CSV
Reads student names and scores from a .csv file using Python’s csv.DictReader.
Stores names and scores in separate lists for processing.
Analyze Data
Calculates important statistics from the scores:
Total number of students
Average (mean) score
Median score
Standard deviation (spread of scores)
Highest score
Lowest score
Generate PDF Report
Uses the FPDF library to create a professional report.

Report includes:

Internship completion certificate title
A table listing each student’s name and score
A statistics section summarizing performance metrics
Internship end date (entered by the user)
Saves the final report as a PDF file.
User Interaction

Asks the user for:

CSV file name (e.g., data.csv)
Output PDF file name (e.g., report.pdf)
Internship end date
After processing, confirms that the report has been generated.

Technologies Used:

Python
CSV module (for reading data)
Statistics module (mean, median, stdev)
FPDF (for PDF generation)

Key Features:
Completely automated from reading raw data to generating a polished PDF.
Handles statistical calculations without manual effort.
Produces a professional, printable certificate/report.

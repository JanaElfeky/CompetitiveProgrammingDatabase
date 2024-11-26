# CompetitiveProgrammingDatabase
Project Overview
This project involves creating a database-driven application that gathers, organizes, and presents information about competitive programming problems, contests, users, and teams. The application provides advanced analytics and insights beyond the default functionalities available on platforms like Codeforces, offering a powerful tool for competitive programming enthusiasts, teams, and organizations.

The project is divided into two main components:

Data Collection and Database Integration: Using Python for web scraping and a MySQL database for structured data storage.
Client Application: A Python-based GUI application built with Tkinter that interacts with the database, providing users with various querying and visualization features.
Features
1. Login Functionality
Users can log in using their Codeforces screen name to:

View all the problems they have attempted.
See all the competitions they have participated in.
2. Competitions by User
Display all competitions authored by a specific user (writer).

3. Problems by Tag
List all problem sets filtered by a specific tag (e.g., dynamic programming, graphs).

4. Programming Language Analytics
Show the top 5 programming languages used to solve problems, ranked by:

Speed efficiency.
Memory efficiency.
5. Top User Rankings
Provide leaderboards for users based on:

Activity Streak: Top 10 users by the number of consecutive days spent on the site.
Problems Solved: Top 10 users with the highest problem-solving count.
Total Contest Scores: Top 10 users in Div. 1 & Div. 2 contests.
6. Top Organizations
Rank the top 5 organizations by the average user ratings in Div. 1 & Div. 2 contests, categorized by country.

7. Participation Efficiency
List the top 5 users by contest participation frequency relative to their registration period on the site.

8. AUC Users Rankings
Highlight the top 10 users from AUC (American University in Cairo) based on their overall rating in Div. 1 & Div. 2 contests.

9. Egyptian Problem Set Statistics
Display the top 5 most attempted problem sets by users from Egypt.

Technologies Used
1. Backend
Python:
For web scraping Codeforces data and automating data collection.
Libraries used: requests, BeautifulSoup, and pandas.
MySQL:
For structured data storage and efficient querying.
Remote hosting ensures scalability and accessibility.
2. Frontend
Tkinter:
To build an interactive and user-friendly GUI.
Users can input queries and view results seamlessly.

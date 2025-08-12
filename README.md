# League of Legends Champion Statistics Database

A web application for viewing and managing performance statistics for League of Legends champions, including win rates, pick rates, and matchups. This project was built using PHP and an Oracle SQL database.

## Features

*   **Database Management:** Uses setup script to create and populate all necessary tables.
*   **Data Manipulation:** UI for Inserting new matchup data and Deleting entire champion roles with cascading effects.
*   **Dynamic Table Viewer:** A user-friendly dropdown to display the contents of any table in the database.
*   **Advanced SQL Queries:** A collection of scripts to perform complex analysis, including Joins, Aggregations, Nested Aggregations, and Division queries.

## Tech Stack

*   **Backend:** PHP (with OCI8 extension)
*   **Database:** Oracle SQL

## Setup and Installation

1.  **Prerequisites:** The script assumes you already have a server set up All OCI commands are commands to the Oracle libraries. To get the file to work, you must place it somewhere where your Apache server can run it.
2.  **Clone the repository:**
    ```
    git clone https://github.com/Nathan-875/LeagueofLegends_Database_project
    ```
3.  **Configure Database Credentials:** In `index.php`, update the database connection variables (`$config["dbuser"]`, `$config["dbpassword"]`) with your personal Oracle credentials.
4.  **Run the Application:**
    *   Place the project files in your web server.
    *   Navigate to `index.php`.
    *   Click the "Reset Database" button to run the `databaseSetup.sql` script and initialize the database.


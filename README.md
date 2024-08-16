# Pokémon JDBC Project

## Overview

This project is a collaborative effort to create a database system for storing and retrieving information about Pokémon generations. The project consists of three databases, each representing a different Pokémon generation. Using SQL, we implemented queries to retrieve various data points from these databases. Additionally, we developed a Java Database Connectivity (JDBC) application to interact with our databases programmatically.

## Project Structure

- **Database 1:** Pokémon Generation I
- **Database 2:** Pokémon Generation II
- **Database 3:** Pokémon Generation III

Each database contains detailed information about the Pokémon, including attributes like species, types, stats, and abilities.

## Features

- **SQL Queries:** We used SQL to query and manipulate the data within each database. This includes retrieving specific Pokémon based on certain criteria, updating stats, and more.
- **JDBC Integration:** Our JDBC application allows us to connect to the databases, execute SQL queries, and display the results in a user-friendly manner.
- **Data Management:** Efficient management of Pokémon data, including the ability to add, update, and delete records.

## Setup and Usage

### Prerequisites

- Java Development Kit (JDK)
- MySQL or any compatible SQL database
- JDBC Driver for MySQL

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/jumpshot7/Pokemon-JDBC-Project
   ```

2. Import the project into your preferred IDE.

3. Set up the databases by executing the SQL scripts provided in the `databases/` directory.

4. Update the JDBC connection details in the Java files:
   ```java
   String url = "jdbc:mysql://localhost:3306/pokemon_generation";
   String user = "root";
   String password = "your_password";
   ```

5. Run the JDBC application:
   ```bash
   java -jar PokemonJDBC.jar
   ```

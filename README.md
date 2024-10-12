# Bookstore Fullstack Application

## Overview

This repository contains a fullstack application for a bookstore. The application is containerized using Docker and orchestrated with Docker Compose.

## Tech Stack

- **Backend**: Node.js, Express, Sequelize
- **Frontend**: React, Bootstrap
- **Database**: SQLite (via Sequelize ORM)
- **Containerization**: Docker
- **Orchestration**: Docker Compose

## Getting Started

These instructions will help you set up and run the application using Docker and Docker Compose.

### Prerequisites

- Docker
- Docker Compose
- Node.js and npm (for local script execution)

### Setting Up the Project

1. **Clone the repository**:

   
bash
   git clone 
   cd bookstore-fullstack
   



2. **Navigate to the Backend Directory**:

   
bash
   cd bookstore-app
   



3. **Install Backend Dependencies**:

   
bash
   npm install
   



### Import Data from CSV

1. **Place Your CSV File**:

   Make sure your CSV file is in the correct format and place it in an accessible location in the backend directory.

2. **Run the Import Script**:

   With your CSV file in place, import the data using the Node.js script provided. Replace `path/to/your/data.csv` with the actual path to your CSV file:

   
bash
   node importData.js path/to/your/data.csv
   



   This will read your CSV file and populate the database with the initial data.

### Run the Application with Docker Compose

1. **Navigate Back to the Root Directory**:

   
bash
   cd ..
   



2. **Build and Run the Containers**:

   Execute the following command to build and start the Docker containers for both frontend and backend services:

   
bash
   docker-compose up --build
   



3. **Access the Application**:

   - **Frontend**: [http://localhost:3001](http://localhost:3001)
   - **Backend**: [http://localhost:3000](http://localhost:3000)

### Features

- **Shop Page**: Displays a list of books with their authors and available stores. Allows marking a book as sold.
- **Stores Page**: Displays a list of stores with search and sort functionalities. Includes functionality to add a new store.
- **Mock Server**: Supports switching between a mock server and the actual backend using an environment variable.

### Notes

- Ensure Docker is running on your machine.
- The `docker-compose.yml` file orchestrates both frontend and backend services.

## Deliverables

- The code is submitted as a public repository on GitHub.
- This README includes instructions on how to get the containers up and running.

## Time Spent

- 6 hours

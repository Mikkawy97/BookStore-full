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

### Running the Application

1. **Clone the repository**:

  
2. **Build and run the containers**:

3. **Access the application**:

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

- 6 hours.

   

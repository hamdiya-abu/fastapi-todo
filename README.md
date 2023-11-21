# FastAPI ToDo App

A simple ToDo application built with FastAPI, SQLAlchemy, MySQL, and Docker.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [API Documentation](#api-documentation)
- [Database Configuration](#database-configuration)
- [Docker](#docker)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a ToDo application built using the FastAPI framework, SQLAlchemy ORM for database interaction, MySQL as the database engine, and Docker for containerization.

## Features

- Create, read, update, and delete ToDo tasks.
- RESTful API using FastAPI.
- Data storage in MySQL database with SQLAlchemy ORM.
- Containerized with Docker for easy deployment.

## Requirements

Make sure you have the following installed on your machine:

- [Python](https://www.python.org/) (3.7 or higher)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hamdiya-abu/fastapi-todo.git
   cd fastapi_todo
2. Create a virtual environment (optional but recommended):
   python -m venv venv
# On Windows: .\venv\Scripts\activate
# On Linux/Mac: source venv/bin/activate

3. Install dependencies:
  pip install -r requirements.txt

4. Running the App
 uvicorn main:app --reload

##Configure the database connection in the app/database.py file.
DATABASE_URL = "mysql+mysqlconnector://user:password@localhost/dbname"

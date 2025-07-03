# Express.js + PostgreSQL CRUD API

A simple RESTful API built with Express.js that connects to a PostgreSQL database to perform CRUD operations on a `users` table.

## Table of Contents

[Features](#features)  
[Prerequisites](#prerequisites)  
[Setup Instructions](#setup-instructions)  
[API Endpoints](#api-endpoints)  
[Example Requests](#example-requests)  
[Error Handling](#error-handling)  
[Notes](#notes)

## Features

Connects to PostgreSQL database using `pg` library  
CRUD operations on users (Create, Read, Update, Delete)  
Basic input validation and error handling  
RESTful API design

## Prerequisites

[Node.js](https://nodejs.org/) installed  
[PostgreSQL](https://www.postgresql.org/) installed and running  
Basic knowledge of REST APIs

## Setup Instructions

1. Clone or download the project files (or copy the provided code) 

2. Create PostgreSQL database and table:

   Connect to your PostgreSQL server and create a database, e.g., `mydatabase`.

  ## sql
   CREATE TABLE users (
     id SERIAL PRIMARY KEY,
     name VARCHAR(100),
     email VARCHAR(100),
     age INTEGER
   );


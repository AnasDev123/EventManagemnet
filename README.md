# Event Management Platform

## Overview
The Event Management Platform (EMP) is a web application built using Node.js, TypeScript, and MongoDB. 
It provides functionalities to manage events, including adding new events, updating existing ones, deleting events, retrieving events by ID, and listing events with optional filters.

Features
CRUD Operations: Perform Create, Read, Update, and Delete operations on events.
Filtering: List events with optional filters based on event name, organizer, and date.
Secure: Utilizes TypeScript for type safety and MongoDB for data persistence.

Project setup:-
Clone the repository: git clone 
Install dependencies: git install 

Create a .env file in the root directory with the following content:
PORT              # Port number for the server
MONGODB_URI   # MongoDB connection URI

Start the development server:
npm run dev


API Endpoints
POST /api/event: Add a new event.
PUT /api/event/:id: Update an existing event.
DELETE /api/event/:id: Delete an event.
GET /api/event/:id: Retrieve an event by its ID.
GET /api/events: List all events with optional filters.

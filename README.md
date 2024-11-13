# Event Scheduling System

A simple Event Scheduling System implemented in Go that provides both a Command Line Interface (CLI) and a RESTful API to manage events. Users can add, view, update, and delete events either via terminal commands or HTTP requests.

## Features

- **CLI Interface**:
  - View all events
  - View event by ID
  - Add a new event
  - Update event by ID
  - Delete event by ID
  - Interactive terminal-based menu

- **RESTful API**:
  - `GET /events`: View all events
  - `GET /events/{id}`: View a specific event by ID
  - `POST /events`: Create a new event
  - `PUT /events/{id}`: Update an event by ID
  - `DELETE /events/{id}`: Delete an event by ID

## Installation

To run the Event Scheduling System, you need to have Go installed on your machine. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/event-scheduling-system.git
   cd event-scheduling-system

# ToDo Application

This is a React-based ToDo application that allows users to add, delete, and update tasks. All tasks are managed through API requests, ensuring persistent storage and retrieval.
[DEMO LINK](https://eeoneishin.github.io/ToDo_APP/)

## Features

- **Add Tasks**: Users can add new tasks to their to-do list.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Update Tasks**: Modify existing tasks to keep information up-to-date.
- **API Integration**: Tasks are managed via API requests, ensuring data persistence.

## Usage

- **Adding a Task**:
  - Navigate to the input field at the top of the application.
  - Enter the task description.
  - Press the "Add" button or hit "Enter" to add the task.

- **Deleting a Task**:
  - Click on the "Delete" icon/button next to the task you wish to remove.

- **Updating a Task**:
  - Click on the task description to enable editing.
  - Make the desired changes.
  - Press "Enter" or click outside the input field to save the changes.

## API Endpoints

The application interacts with the following API endpoints:

- **Get All Tasks**: `GET /api/tasks`
- **Add a New Task**: `POST /api/tasks`
- **Update a Task**: `PUT /api/tasks/:id`
- **Delete a Task**: `DELETE /api/tasks/:id`

*Note*: Ensure that the API server is running and accessible for the application to function correctly.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Eeoneishin/ToDo_APP.git
   cd ToDo_APP
   ```
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Start the Application**:
   ```bash
   npm start
   ```
   The application will run on `http://localhost:3000/` by default.

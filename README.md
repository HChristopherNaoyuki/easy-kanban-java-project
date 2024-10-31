# Easy Kanban

EasyKanban is a simple task management application designed to help users organize and track their tasks efficiently. It features a user-friendly interface built with Java Swing, allowing users to log in, add tasks, and view task details.

## Features

- **User Authentication**: Simple login mechanism with predefined credentials.
- **Task Management**: Add multiple tasks with details such as name, description, developer details, duration, and status.
- **Task ID Generation**: Unique task IDs are generated based on task name and developer details.
- **Input Validation**: Checks for task description length and provides user feedback.
- **Report Generation**: Displays total task duration (feature coming soon).

## Requirements

- Java Development Kit (JDK) 8 or higher
- Integrated Development Environment (IDE) for Java (e.g., IntelliJ IDEA, Eclipse)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HChristopherNaoyuki/PROG5121-POE.git
   cd easykanban
   ```

2. Compile and run the application:
   ```bash
   javac -d bin src/easykanban/*.java
   java -cp bin easykanban.EasyKanban
   ```

## Usage

1. Start the application by running `EasyKanban`.
2. Log in using the credentials:
   - Username: `admin`
   - Password: `password`
3. Choose from the available options:
   - Add tasks
   - Show report (coming soon)
   - Quit

### Adding Tasks

When adding tasks, provide the following information:
- Task Name
- Task Description (must be less than 50 characters)
- Developer Details (First and Last Name)
- Task Duration (in hours)
- Task Status (To Do, Done, Doing)

## Testing

The application includes a basic unit test class `TaskTest` to validate:
- Task description length
- Task ID generation
- Total hours calculation

Run the test class to ensure all functionality is working as expected.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

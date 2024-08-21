# Flutter To-Do List App with Hive Database

## Introduction
This Flutter application is a simple to-do list management tool that allows users to create, update, and delete tasks. The app utilizes the Hive database to store and manage the task data, providing a reliable and efficient way to persist user data.

## Features
1. **Task Management**: Users can create new tasks, mark tasks as completed, and delete tasks.
2. **Persistent Storage**: Task data is stored in the Hive database, ensuring that the user's to-do list is preserved even after the app is closed or the device is restarted.
3. **Intuitive User Interface**: The app features a clean and user-friendly interface, making it easy for users to navigate and manage their tasks.
4. **Responsive Design**: The app is designed to work seamlessly on a variety of screen sizes and devices, providing a consistent user experience.

## Technologies Used
- **Flutter**: The app is built using the Flutter framework, a cross-platform mobile development toolkit that allows for the creation of high-performance, visually-appealing applications.
- **Hive Database**: The Hive database is used as the primary data storage solution for the app, providing a fast and lightweight NoSQL database that is well-suited for mobile applications.
- **Dart Programming Language**: The app is written in Dart, the programming language used for Flutter development, which offers a modern, type-safe, and object-oriented approach to app development.

## Getting Started
To get started with the To-Do List app, follow these steps:

1. **Clone the Repository**: Start by cloning the repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/flutter-todo-app.git
   ```

2. **Install Dependencies**: Navigate to the project directory and install the required dependencies using the following command:

   ```
   flutter pub get
   ```

3. **Run the App**: Once the dependencies are installed, you can run the app on your preferred device or emulator using the following command:

   ```
   flutter run
   ```

## Project Structure
The project is structured as follows:

- `lib/`: Contains the main Flutter application code
  - `main.dart`: The entry point of the application
  - `models/`: Contains the data models used in the app, such as the `Task` model
  - `screens/`: Contains the UI screens of the app, such as the home screen and the task creation screen
  - `services/`: Contains the Hive-related services, such as the `HiveService` for managing the task database
  - `widgets/`: Contains reusable UI components used throughout the app, such as the `TaskCard` widget
- `android/` and `ios/`: Contains the platform-specific code for Android and iOS, respectively
- `pubspec.yaml`: The Flutter project configuration file, which specifies the dependencies and assets used in the app

## Future Improvements
While the current version of the To-Do List app provides a solid set of features, there are always opportunities for improvement. Some potential future enhancements include:

1. **Task Sorting and Filtering**: Allowing users to sort and filter their tasks based on various criteria, such as due date, priority, or completion status.
2. **Task Reminders**: Implementing a feature that allows users to set reminders for their tasks, helping them stay on top of their to-do list.
3. **Sharing and Collaboration**: Enabling users to share their to-do lists with others and collaborate on tasks.
4. **User Accounts and Synchronization**: Integrating user accounts and task synchronization across devices, allowing users to access their to-do lists from multiple devices.

## Conclusion
The Flutter To-Do List App with Hive Database provides a simple and effective way for users to manage their tasks. By leveraging the Hive database for data storage, the app ensures that user data is reliably preserved, while the intuitive user interface and responsive design make the app a pleasure to use. As the app evolves, there are plenty of opportunities for further enhancements to improve the user experience and provide additional features to meet the needs of modern task management.

## Images
![image](https://github.com/user-attachments/assets/07a98309-9c27-4e3c-a923-20651dd058f5)


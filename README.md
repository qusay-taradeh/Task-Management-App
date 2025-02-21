# Task Management App
Task Management App for multiple users enabling sign-up, sign-in, and comprehensive to-do task management.

## Summary
Implementation of a Task Management Application that allows users to create an account using their email address and password. Once logged in, users can add new to-do tasks, view current tasks, and mark tasks as completed. The application offers a robust user authentication system, a dynamic home layout with a navigation drawer, and multiple features to manage tasks, notifications, and profiles.

## Specifications

- **User Management:**  
  Users can sign up with an email, first name, last name, and password. A "remember me" feature is available during sign-in, along with secure authentication and logout.

- **Home Layout:**  
  A navigation drawer provides quick access to:
  - **Today:** Displays tasks for the current day.
  - **New Task:** Allows adding tasks with details like title, description, due date/time, priority, reminders, and edit/delete options.
  - **All & Completed:** Lists all tasks (grouped by day) and completed tasks separately.
  - **Search & Profile:** Enables task filtering by date range and profile editing (email and password).
  - **Logout:** Securely logs out the user.

- **Additional Features:**  
  - Modify tasks (edit, complete, share via email, delete).
  - Set custom notifications and snooze reminders.
  - Import tasks via a dummy REST API.
  - Support dark/light modes.
  - Sort tasks based on user-defined priorities (defaulting to Medium).

- **UI Design:**  
  The app leverages Android components (layouts, intents, notifications, SQLite, animations, fragments, and shared preferences) to deliver an engaging and intuitive user interface.

## Authors 
Qusay Taradeh, Muayad Karakra

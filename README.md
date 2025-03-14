# Fitness Accountability App

A Flutter-based mobile application that helps users form and maintain healthy habits by leveraging group accountability.

## Features

- **User Authentication**: Secure login and registration with email, Google, and other social providers
- **Habit Tracking**: Create, track, and manage daily habits
- **Group Accountability**: Join or create groups to stay motivated with friends
- **Progress Visualization**: View your progress with intuitive charts and statistics
- **Verification System**: Submit proof of habit completion for accountability
- **Notifications**: Reminders to complete habits and group activity updates

## Tech Stack

- **Frontend**: Flutter
- **State Management**: Riverpod
- **Backend**: Supabase & Firebase
- **Navigation**: Go Router
- **Storage**: Shared Preferences, Firebase Storage
- **Authentication**: Firebase Auth, Supabase Auth

## Getting Started

### Prerequisites

- Flutter SDK (3.0.0 or higher)
- Dart SDK (3.0.0 or higher)
- Android Studio / VS Code with Flutter extensions

### Installation

1. Clone the repository
   ```
   git clone https://github.com/sngweizhi/fitness-accountability-app.git
   ```

2. Navigate to the project directory
   ```
   cd fitness-accountability-app
   ```

3. Install dependencies
   ```
   flutter pub get
   ```

4. Run the app
   ```
   flutter run
   ```

## Project Structure

The project follows a feature-first architecture with clean architecture principles:

```
lib/
├── core/            # Core functionality, constants, themes, utilities
├── features/        # Feature modules
│   ├── auth/        # Authentication feature
│   ├── habits/      # Habit tracking feature
│   └── groups/      # Group accountability feature
├── firebase_options.dart
├── main.dart        # Entry point
└── routes.dart      # Application routes
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
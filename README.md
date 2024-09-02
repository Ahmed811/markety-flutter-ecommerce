# E-Commerce Flutter App



## Overview

This is a fully functional e-commerce application built using Flutter. The app allows users to browse products by category, add items to their favorites, and complete purchases through a checkout process. Authentication is handled via Firebase, allowing users to register, sign in, and sign out securely.

## Features

- **User Authentication:** Users can register, sign in, and sign out using Firebase.
- **Product Categories:** Browse products by different categories.
- **Favorites:** Users can add products to their favorites list.
- **Checkout:** Complete the purchase of selected items.
- **State Management:** The app uses `flutter_bloc` for state management.
- **Dependency Injection:** Managed via `get_it`.

## Screenshots

### Home Screen
<img src="https://github.com/user-attachments/assets/f1faeb7e-b1db-4c8c-b0e7-64265c9063a0" alt="Home Screen" width="300"/>

### Product Categories
<img src="https://github.com/user-attachments/assets/e44636e4-1522-4212-87be-0fc74c97d6bc" alt="Home Screen" width="300"/>

### Checkout
<img src="https://github.com/user-attachments/assets/04e89969-c471-474a-a870-43000869fddf" alt="Home Screen" width="300"/>
<img src="https://github.com/user-attachments/assets/62bc6e41-09c2-440d-9fe5-c4e01532d6ef" alt="Home Screen" width="300"/>

## Demo Video
[![IMAGE ALT TEXT HERE](https://github.com/user-attachments/assets/f1faeb7e-b1db-4c8c-b0e7-64265c9063a0)](https://www.youtube.com/watch?v=K0b-hCk_vV8)


<div align="left">
      <a href="https://www.youtube.com/watch?v=5yLzZikS15k">
         <img src="https://img.youtube.com/vi/5yLzZikS15k/0.jpg" style="width:100%;">
      </a>
</div>
## Packages Used

- **`firebase_auth:`** Firebase Authentication for handling user sign-in, sign-out, and registration.
- **`firebase_core:`** Core Firebase SDK for initializing Firebase in your Flutter app.
- **`cloud_firestore:`** Cloud Firestore for storing and retrieving product and user data.
- **`flutter_svg:`** To render SVG images in the app.
- **`flutter_bloc:`** For state management, providing separation between business logic and UI.
- **`dartz:`** For functional programming in Dart.
- **`get_it:`** Dependency injection for managing app-wide instances and services.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Ahmed811/markety-flutter-ecommerce.git
    ```
2. Navigate to the project directory:
    ```bash
    cd e-commerce-flutter-app
    ```
3. Install dependencies:
    ```bash
    flutter pub get
    ```
4. Run the app:
    ```bash
    flutter run
    ```

## Getting Started

To get started with this project, you'll need to configure your Firebase project. Follow the official [Firebase Setup Guide](https://firebase.google.com/docs/flutter/setup) to set up Firebase for iOS and Android.

## Contribution

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy Coding! 😊

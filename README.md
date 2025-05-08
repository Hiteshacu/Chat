# 💬 Android Chat Application

A real-time chat application developed using **Android Studio** and **Firebase Realtime Database**. The app enables user authentication and messaging between users with instant updates and a clean UI.

---

## 📌 Table of Contents

1. [Overview](#overview)  
2. [Key Features](#key-features)  
3. [Tech Stack](#tech-stack)  
4. [Project Setup](#project-setup)  
5. [Firebase Configuration](#firebase-configuration)  
6. [App Architecture](#app-architecture)  
7. [User Guide](#user-guide)  
8. [Screenshots](#screenshots)  
9. [Limitations](#limitations)  
10. [Planned Enhancements](#planned-enhancements)  
11. [License](#license)  
12. [Author & Credits](#author--credits)

---

## 🧩 Overview

This Android chat application allows users to register, log in, and send messages in real time. It leverages **Firebase Authentication** for login/sign-up and **Firebase Realtime Database** for instant message syncing.

---

## 🚀 Key Features

- 🔐 User registration and login  
- 💬 One-to-one real-time messaging  
- 🧠 Firebase Realtime Database integration  
- 📲 Material Design UI  
- ✅ Online status indicator  
- ⏱ Message timestamps  
- 🔄 Auto-refresh with live updates

---

## 🛠 Tech Stack

- **Programming Language:** Java / Kotlin *(mention your choice)*  
- **IDE:** Android Studio  
- **Backend:** Firebase Realtime Database  
- **Authentication:** Firebase Authentication  
- **UI Design:** XML with Material Components  
- **Libraries Used:** Glide (optional for image loading), Firebase SDK

---

## ⚙️ Project Setup

1. Clone this repository:
   ```bash
   https://github.com/Hiteshacu/Chat.git
   
Open the project in Android Studio.

Sync Gradle files.

Add your google-services.json file to the /app directory.

🔧 Firebase Configuration
Create a new Firebase project at Firebase Console.

Enable Authentication (Email/Password).

Enable Realtime Database and set rules:

json
Copy
Edit
{
  "rules": {
    ".read": "auth != null",
    ".write": "auth != null"
  }
}
Download the google-services.json and place it in the app/ folder.

🏗 App Architecture
graphql
Copy
Edit
com.yourapp.chatapp/
├── activities/         # Login, Register, ChatActivity
├── adapters/           # RecyclerView adapters for messages
├── models/             # User.java, Message.java
├── utils/              # Firebase utilities, constants
├── layout/             # XML UI layouts
└── drawable/           # Icons, assets
👨‍💻 User Guide
Sign Up: Create a new user account with email & password.

Login: Log in with your registered credentials.

Chat: Select a user to begin messaging in real time.

Logout: Tap the logout button in the menu.

🖼 Screenshots
(Replace with actual screenshots)



🐞 Limitations
No group chat support

No push notifications

No media (images/files) sharing

Basic UI for demonstration purposes

📈 Planned Enhancements
 Group chat functionality

 Push notifications using FCM

 Typing indicator

 Profile picture upload and avatars

 Message read receipts

📜 License
This project is licensed under the MIT License.

👨‍🎨 Author & Credits
Developer: [Your Name]

Tools: Android Studio, Firebase

Libraries: Firebase SDK, Material Design

Special thanks to the Android & Firebase community for documentation and examples

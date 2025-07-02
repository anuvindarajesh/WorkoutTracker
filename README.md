# 🏋️‍♀️ Workout Tracker - Android App

A simple, responsive Android workout tracking app built using WebView and HTML/CSS/JavaScript. This app lets you log and view workouts based on muscle groups, track workout history using an interactive calendar, and manage your routine — all from your phone.

---

## 🚀 Features

- 💪 Muscle group-based workout logging (add/edit/delete muscle groups with emojis)
- 📅 Calendar view to track workout history
- 🗑️ Delete workouts with a warning
- 🧠 Automatically remembers your workouts using device storage (no backend needed)
- ➕ Automatically records "0kg" if no weight is entered
- 🔢 Weight input accepts only numbers and opens numeric keypad on phones
- 📱 Responsive design works on all screen sizes
- 🌐 Built using WebView to render HTML/CSS/JS
- 🌙 Dark-themed UI for better readability
- ✅ Full offline support (everything runs locally)

---

## 📸 Screenshots

![WhatsApp Image 2025-07-02 at 13 11 46 (1)](https://github.com/user-attachments/assets/b568e6ac-67a0-4208-aaa4-3bd624e2bb51)
![WhatsApp Image 2025-07-02 at 13 11 46](https://github.com/user-attachments/assets/2707fb45-a6a6-4b9a-b6f2-1abbd4ff885d)
![WhatsApp Image 2025-07-02 at 13 11 47](https://github.com/user-attachments/assets/bd922950-ba14-4c7b-b846-c5ff7ced8e05)
![WhatsApp Image 2025-07-02 at 13 11 47 (1)](https://github.com/user-attachments/assets/5eb01c65-b347-449d-8560-c703b2246e16)
![WhatsApp Image 2025-07-02 at 13 11 47 (2)](https://github.com/user-attachments/assets/722582b4-6a10-4e92-ad44-243023ef7c46)
![WhatsApp Image 2025-07-02 at 13 11 47 (3)](https://github.com/user-attachments/assets/19a3dbef-3c86-47a2-8b71-ce73fad092a7)


---

## 📁 Tech Stack

- **Android Studio** (Java)
- **WebView**
- **HTML + Tailwind CSS**
- **JavaScript + localStorage**

---

## 📦 Installation

### 1. Clone the Repository

bash
git clone https://github.com/<your-username>/Workout-Tracker.git
cd Workout-Tracker

### 2. Open in Android Studio

•Open Android Studio
•Click File → Open…
•Select the project directory (Workout-Tracker)
•Let Gradle sync

### 3. Run the App
•Connect your Android device or use the emulator
•Click the green Run ▶️ button

⸻

## 🔧 How It Works
•The app uses a WebView to load index.html from the assets/ folder
•Tailwind CSS and Google Fonts are loaded via CDN
•All logic is handled in JavaScript (no backend required)
•Workouts and muscle groups are stored using localStorage
•Data persists across app restarts and remains until app data is cleared/uninstalled

⸻

## 📱 Building the APK
•Go to Build → Build Bundle(s) / APK(s) → Build APK(s)

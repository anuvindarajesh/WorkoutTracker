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

![WhatsApp Image 2025-07-02 at 10 06 02 (1)](https://github.com/user-attachments/assets/e8f02c72-168f-43f8-91f9-2c8e8130808b)
![WhatsApp Image 2025-07-02 at 10 06 02](https://github.com/user-attachments/assets/8162bdf0-8182-4b35-832b-969b8b382422)
![WhatsApp Image 2025-07-02 at 10 06 01](https://github.com/user-attachments/assets/d59fdb8a-e041-46d5-98fd-f62bd7a5f389)

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

# SOUQÉ 🛒

**Your Smart Grocery Shopping Assistant**
An intelligent mobile application built with Flutter & Firebase to enhance the grocery shopping experience through allergy warnings, personalized suggestions, and real-time delivery tracking.

---

## 🏫 Project Information

* **University:** Benha University, Faculty of Engineering (Shoubra)  
* **Department:** Communications and Computer Engineering  
* **Course:** Mobile Computing 

---

## 🧑‍💻 Team Members

* **Farida Waheed Abdelbary**
* **Nourhan Farag Mohamed**
* **Malak Mounir Abdellatef**
* **Nour Hesham El Sayed**

---

## 📖 Overview

SOUQÉ is designed to streamline your grocery shopping while keeping your health and preferences in mind. Whether you have specific allergies, favorite brands, or want to track your order in real time, SOUQÉ provides a smart and simple solution—all from your smartphone.

This app was created as part of a university graduation project by a dedicated team of four developers passionate about mobile app development and user-centered design.

---

## 🚀 Live Preview



---

## ✨ Features

* 🔐 **Authentication**

  * Google Sign-In
  * Email & Password login
* 👤 **User Profile Management**

  * Edit name, address, and allergies
  * View previous orders
* 🛒 **Smart Shopping**

  * Personalized product suggestions
  * Smart cart and favorites
* ⚠️ **Allergy Alert System**

  * Automatically warns users about allergens in products
* 📍 **Google Maps Integration**

  * Live location and delivery tracking
* 🔄 **Real-time Database**

  * Built with Firebase Firestore for instant updates
* 📦 **Order Status**

  * Monitor order from placement to delivery
* 📱 **Responsive UI**

  * Clean and intuitive interface optimized for Android & iOS
* 🧠 **State Management**

  * Efficient data flow using Provider

---

## 🧠 Architecture

* **Client:** Flutter (Dart)
* **Backend:** Firebase (Auth + Firestore)
* **Maps:** Google Maps API
* **State Management:** Provider Pattern
* **Project Structure:**

  ```
  lib/
  ├── auth/
  ├── models/
  ├── screens/
  ├── services/
  ├── widgets/
  └── main.dart
  ```

---

## 📸 Screenshots

| Home Screen           | Product Detail           | Explore Screen          | Map Tracking         |
| --------------------- | ------------------------ | ------------------------ | -------------------- |
|![homeScreen](https://github.com/user-attachments/assets/5fc89c03-8798-404d-9b81-e66a944ebf99)|![productDetails](https://github.com/user-attachments/assets/a18c5d6f-7ca8-4c54-9ed5-1d4bcc4979c2)|![explore](https://github.com/user-attachments/assets/ae288ca9-ee28-4a4b-83ac-878da1f5d5a3)|![trackOrder](https://github.com/user-attachments/assets/e89c60ba-9e2c-4b66-84eb-51d650cc4896)|

---

## ⚙️ Setup Instructions

### 🔧 Requirements

* Flutter SDK
* Firebase account
* Google Maps API Key

### 📥 Installation

```bash
git clone https://github.com/yourusername/souqe-app.git
cd souqe-app
flutter pub get
```

### 🔐 Firebase Setup

1. Create a Firebase project.
2. Enable **Authentication** (Email/Password & Google).
3. Create **Firestore database**.
4. Download and add:

   * `google-services.json` to `android/app/`
   * `GoogleService-Info.plist` to `ios/Runner/`

### 🗺️ Google Maps API Setup

1. Get API Key from [Google Cloud Console](https://console.cloud.google.com/)
2. Add it to:

   * `android/app/src/main/AndroidManifest.xml`
   * `ios/Runner/AppDelegate.swift`

---

## 📦 Packages Used

| Package                  | Purpose                  |
| ------------------------ | ------------------------ |
| `firebase_core`          | Firebase initialization  |
| `firebase_auth`          | Authentication           |
| `cloud_firestore`        | Realtime database        |
| `google_sign_in`         | Google login             |
| `google_maps_flutter`    | Map integration          |
| `geolocator`             | Location tracking        |
| `provider`               | State management         |
| `awesome_dialog`         | Enhanced dialog messages |
| `intl`                   | Date and time formatting |
| `flutter_launcher_icons` | App icon customization   |

---


## 🧩 Future Improvements

* [ ] Payment Gateway Integration (e.g., Stripe)
* [ ] In-App Notifications for Delivery
* [ ] QR Code Scanning for Products
* [ ] Offline Cart Support
* [ ] Dark Mode Support


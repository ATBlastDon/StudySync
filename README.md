[![Flutter](https://img.shields.io/badge/Flutter-3.0+-blue.svg)](https://flutter.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-Enabled-orange.svg)](https://firebase.google.com/)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](https://opensource.org/licenses/GPL-3.0)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web-lightgrey.svg)](https://flutter.dev/multi-platform)

# StudySync

**StudySync** is a comprehensive educational ecosystem that bridges the gap between students and teachers through two powerful Flutter applications. It revolutionizes classroom management, attendance tracking, academic performance monitoring, and real-time communication in educational institutions.

> 🚀 *Empowering education through seamless digital connectivity*

---

## 🌟 Overview

StudySync consists of two complementary Flutter applications that work together to create a unified educational experience:

### 📱 StudySync Student
A comprehensive mobile companion for students to track their academic journey, stay connected with teachers, and monitor their progress in real-time.

### 🎯 StudySync Teacher  
An intuitive interface designed for educators to manage classes, track attendance, evaluate student performance, and generate detailed reports effortlessly.

**Why StudySync?**
- 🔄 **Real-time Synchronization**: Instant updates across all platforms using Firebase
- 📊 **Data-Driven Insights**: Comprehensive analytics and reporting capabilities
- 🎨 **Modern UI/UX**: Beautiful, intuitive interfaces with smooth animations
- 🔒 **Secure & Reliable**: Firebase authentication and robust data security
- 📱 **Cross-Platform**: Works seamlessly on Android, iOS, and Web

---

## ✨ Key Features

### 👨‍🎓 Student App Features

#### 📊 **Academic Dashboard**
- **Personalized Overview**: View attendance, performance, and notifications at a glance
- **Real-time Updates**: Instant sync of marks, attendance, and subject information
- **Performance Tracking**: Monitor academic progress across all subjects and semesters

#### 📚 **Learning Management**
- **Attendance Tracker**: Comprehensive attendance monitoring by subject and semester
- **Resource Access**: View study materials and class announcements from teachers
- **Optional Subjects**: Manage selected optional subjects and batch preferences

#### 👤 **Profile Management**
- **Real-time Editing**: Update personal and academic information instantly
- **Academic Details**: Manage year, semester, batch, mentor, and roll number
- **Offline Support**: Cached data for seamless experience with limited connectivity

### 👩‍🏫 Teacher App Features

#### 🏫 **Class Management**
- **Comprehensive Dashboard**: Overview of classes, pending tasks, and notifications
- **Student Management**: View approved and pending student profiles with detailed insights
- **Batch Operations**: Approve, reject, or manage multiple students simultaneously

#### 📋 **Attendance System**
- **Interactive Marking**: Smooth interface with animated transitions for attendance marking
- **Real-time Updates**: Instant synchronization of attendance data
- **Historical Tracking**: Complete attendance history and analytics

#### 📊 **Reports & Analytics**
- **PDF Generation**: Create detailed PDF reports with customizable headers and columns
- **Performance Analytics**: Track student performance across subjects and semesters
- **Data Export**: Export attendance and marks data in various formats

#### ⚡ **Advanced Features**
- **Interactive Editing**: Tap-to-edit student marks and attendance records
- **Bulk Operations**: Reset or update multiple records with single actions
- **Real-time Collaboration**: Instant updates visible to students and other teachers

---

## ⚡ Prerequisites

Before running StudySync applications, ensure you have the following installed:

### 🛠️ Development Environment
- **Flutter SDK** (3.0 or later) - [Installation Guide](https://docs.flutter.dev/get-started/install)
- **Dart SDK** (included with Flutter)
- **Android Studio** or **VS Code** with Flutter extension
- **Git** for version control

### 📱 Platform Requirements
- **Android**: Android SDK 21+ (Android 5.0)
- **iOS**: iOS 11.0+ and Xcode 12+
- **Web**: Chrome, Firefox, Safari, or Edge

### ☁️ Firebase Setup
- Firebase project with Firestore, Authentication, and Storage enabled
- Firebase CLI installed - [Installation Guide](https://firebase.google.com/docs/cli)

---

## 🚀 Getting Started

### 📥 Clone the Repository

clone individual repositories:

```bash
git clone https://github.com/ATBlastDon/StudySync_Student.git
git clone https://github.com/ATBlastDon/StudySync_Teacher.git
```

### 🎓 Running StudySync Student

```bash
cd StudySync_Student
flutter pub get
# Add Firebase config:
# - android/app/google-services.json
# - ios/Runner/GoogleService-Info.plist
flutter run
```

### 🏫 Running StudySync Teacher

```bash
cd StudySync_Teacher
flutter pub get
# Add Firebase config:
# - android/app/google-services.json
# - ios/Runner/GoogleService-Info.plist
flutter run
```

### 🌐 Web Build & Deploy (optional)

```bash
# Build for web
flutter build web

# Deploy to Firebase Hosting (if configured)
firebase deploy --only hosting
```

## 🛠️ Development

### 🔧 Common Commands
```bash
# Install dependencies
flutter pub get
```

---

## 📄 License

Both repositories show a **GPL-3.0** license file in the root. Make sure the `LICENSE` file content and any license badges reflect GPL-3.0 consistently.

---

## 👨‍💻 Author & Support

**Atharv Sutar (ATBlastDon)**  
- GitHub: https://github.com/ATBlastDon  
- Email: atharvsutar3102003@gmail.com  
- BuyMeACoffee: https://www.buymeacoffee.com/atblastdon  
- UPI: `atanything@ybl`

---

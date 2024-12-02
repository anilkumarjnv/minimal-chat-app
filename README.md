---

# **Minimal Chat App 💬**  

A lightweight, elegant chat application built with **Flutter** and **Firebase**, designed for real-time, seamless messaging. This app focuses on simplicity while delivering core chat functionalities, perfect for those who appreciate minimalism.  

---

## **🌟 Key Features**  

- **Real-Time Messaging**: Instantly send and receive messages using Firebase Firestore.  
- **Authentication**: Secure login with Firebase Auth (supports email/password or third-party providers).  
- **User Management**:  
  - View all registered users in real-time.  
  - Block or unblock users effortlessly.  
  - Report inappropriate messages or users.  
- **Dynamic Chat Rooms**: Unique chat rooms are automatically generated for one-on-one conversations.  
- **Modern UI Design**: A clean, responsive interface with light and dark mode support.  
- **Cloud Storage Ready**: Easily extendable to include media and file sharing.  
- **Offline Access**: View past messages even when offline.  

---

## **💻 Tech Stack**  

- **Frontend**: Flutter (Dart)  
- **Backend**: Firebase (Firestore, Auth)  
- **State Management**: Provider  
- **UI Enhancements**: Light and Dark Themes  

---

## **📸 Screenshots**  
(Replace with actual image links)  

| ![Screenshot1](assets/screenshots/Screenshot1.jpg) | ![Screenshot2](assets/screenshots/Screenshot2.jpg) |  
|:--------------------------------------------------:|:--------------------------------------------------:|  
| ![Screenshot3](assets/screenshots/Screenshot3.jpg) | ![Screenshot4](assets/screenshots/Screenshot4.jpg) |  

---

## **🚀 Getting Started**  

### **Prerequisites**  

- Flutter SDK ([installation guide](https://docs.flutter.dev/get-started/install))  
- Firebase project setup ([Firebase Console](https://console.firebase.google.com/))  

---

### **Setup Instructions**  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/minimal-chat-app.git  
   cd minimal-chat-app  
   ```  

2. Install dependencies:  
   ```bash  
   flutter pub get  
   ```  

3. Set up Firebase:  
   - Create a Firebase project and add your app to it.  
   - Download and place the `google-services.json` (Android) or `GoogleService-Info.plist` (iOS) file in your project.  
   - Configure `firebase_options.dart` using the [FlutterFire CLI](https://firebase.flutter.dev/docs/cli/).  

4. Run the application:  
   ```bash  
   flutter run  
   ```  

---

## **⚙️ How It Works**  

1. **Real-Time Messaging**: Users send and receive messages instantly via Firestore's real-time capabilities.  
2. **Chat Rooms**: Each conversation generates a unique, sorted chat room ID to ensure seamless one-on-one communication.  
3. **User Management**:  
   - The app fetches all registered users.  
   - Users can block or report inappropriate behavior.  
4. **Themes**: Light and dark themes enhance the user experience and cater to personal preferences.  

---

## **📦 Dependencies**  

- **[Provider](https://pub.dev/packages/provider)**: For state management.  
- **[Firebase](https://firebase.google.com/)**: Backend services for authentication and real-time messaging.  
- **[Flutter](https://flutter.dev/)**: Cross-platform development.  

---

## **✨ Future Enhancements**  

- Add group chat functionality.  
- Support media and file sharing.  
- Push notifications for new messages.  
- Message encryption for enhanced privacy.  

---

## **🤝 Contributions**  

We welcome contributions! If you have suggestions, encounter bugs, or want to add new features, feel free to open an issue or submit a pull request.  

---

## **🙏 Acknowledgments**  

- **Firebase** for providing seamless backend services.  
- The amazing **Flutter** community for their support and resources.  

---

## **⭐ Show Your Support**  

If you enjoyed this project or found it helpful, consider giving it a ⭐ on GitHub!  

--- 

This README captures all the essential information while keeping it clean and professional.

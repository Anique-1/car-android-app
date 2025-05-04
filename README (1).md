# 🚗 Car Selling App using Firebase and Android Studio

This is a mobile application built using **Android Studio** that allows users to **register/login** and perform full **CRUD operations** on car listings using **Firebase Authentication** and **Firebase Realtime Database**.

---

## 📱 Features

- 🔐 **User Authentication** using Firebase (Register & Login)
- 🏠 **Splash Screen** for initial branding
- 📋 **Add Car Details** (Model, Driven KM, Price, Manufacture Year)
- 🔁 **View Car Listings** using RecyclerView
- ✏️ **Update Car Records**
- ❌ **Delete Car Records**
- 📡 **Realtime Sync** with Firebase Database

---

## 🛠️ Tech Stack

- **Android Studio**
- **Java** (or Kotlin)
- **Firebase Authentication**
- **Firebase Realtime Database**
- **RecyclerView**

---

## 🧱 App Structure

```
Splash Screen ➝ Login/Register ➝ Home Screen
                              ⬇
           RecyclerView (List of Cars with Update/Delete buttons)
```

---

## 📂 Firebase Database Structure

```json
{
  "Users": {
    "userID1": {
      "carID1": {
        "model": "Honda Civic",
        "driven": "25000",
        "price": "700000",
        "year": "2019"
      },
      ...
    }
  }
}
```

---

## 🖼️ Screenshots

> Add your app screenshots here (optional)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/car-selling-app.git
```

### 2. Open in Android Studio

- File > Open > Select the cloned folder

### 3. Connect Firebase

- Tools > Firebase > Authentication & Realtime Database  
- Enable Email/Password Sign-in method  
- Set up Realtime Database and rules

### 4. Run the App

- Connect an emulator or physical device  
- Click "Run" or use `Shift + F10`

---

## 📌 Future Improvements

- Add image upload for cars (using Firebase Storage)
- Search and filter functionality
- Profile page with logout and user settings
- Use Firestore for more scalable data handling

---

## 👨‍💻 Author

**Your Name** – [Your GitHub Profile](https://github.com/yourusername)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
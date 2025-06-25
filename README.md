# 🎧 E-Commerce App for Electronics – Flutter + Firebase + Stripe (Payment Gateaway)

[![Watch the Demo](https://img.youtube.com/vi/zAYBIg0TOOw/0.jpg)](https://youtu.be/zAYBIg0TOOw?si=m2IUFcd0JHm01yRE) Click The Image To See The Video.

## 🔗 Download APK  
👉 [Click here to download the release APK](https://drive.google.com/file/d/1T7jflMVUf5pM8q2zggev_x-4MC_RoiPW/view?usp=sharing)

---

## 📱 Overview
A full-stack e-commerce mobile app built with **Flutter** using Firebase for backend. This app is focused on selling **electronics products** like headphones, speakers, etc.

Features include:

- 🛍️ Browse products by category  
- 🔍 Search & filter products  
- 🧾 Order placement and tracking  
- 👤 Login & Signup with Firebase Auth  
- 🧠 Onboarding for new users  
- 🛠 Admin panel for managing products and orders  
- 💾 Local storage with SharedPreferences  
- 💳 Payment integration with Stripe 

---

## 🧑‍💻 Tech Stack

| Frontend      | Backend        | State Management |
|---------------|----------------|------------------|
| Flutter       | Firebase Auth  | SetState / Cubit |
| Dart          | Cloud Firestore| SharedPreferences |
| Dio (optional)| Firebase Storage| --              |

---

## 🔑 Admin Panel

The app includes a hidden admin login that allows:

- ➕ Add/Edit/Delete products  
- 📦 View all user orders  
- 📬 Update order delivery status

---

## 📂 Project Structure

```bash
lib/
├── Admin/
│   ├── add_product.dart
│   ├── admin_login.dart
│   └── home_admin.dart
├── pages/
│   ├── login.dart
│   ├── signup.dart
│   ├── home.dart
│   ├── onboarding.dart
│   └── product_detail.dart
├── services/
│   ├── constant.dart
│   ├── shared_pref.dart
│   └── database.dart
├── widget/
│   └── support_widget.dart
├── main.dart

---

🚀 Author
Zeyad Mohamed Abdelwahab
📧 xzyaddev@gmail.com

# Grama-Khata 📒

## Android App Development using GenAI – Micro-Finance Digital Ledger

A simplified digital ledger application designed for village grocery stores and small shopkeepers to manage customer credit transactions digitally.

---

## 📌 Problem Statement

Many small grocery stores in villages still maintain customer credit records in physical notebooks (“Vahis”).

When records are lost, damaged, or mismanaged, it can lead to:

- Financial loss
- Confusion between customers
- Social friction in the community

Shopkeepers need a simple, easy-to-use digital solution without complicated accounting systems.

---

## 💡 Project Vision

Grama-Khata is a lightweight digital ledger application focused on maintaining trust-based micro-finance transactions in rural communities.

Instead of complex accounting dashboards, the app provides a simple:

- Give (Credit) ➕
- Take (Payment) ➖

workflow for managing dues.

The application also supports:

- Real-time balance tracking
- WhatsApp/SMS payment reminders
- Offline-first data storage
- Simple UI for rural shopkeepers

---

## 🚀 Features

### 👤 Customer Profile Management

- Add customer name
- Add customer photo
- Avoid confusion between customers with similar names

### 💰 Transaction Management

- Add credit transactions
- Record customer payments
- Automatic net balance calculation

### 📊 Due Dashboard

- Displays customers sorted by highest due amount
- Easy identification of pending payments

### 📲 WhatsApp / SMS Reminder

- One-tap reminder sending
- Pre-filled payment reminder message

#### Example Message

```text
Namaskara, your due at [Shop Name] is ₹[Amount].
```

### 📶 Offline First

- Uses Room Database for local data storage
- Works without internet connectivity

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Android Studio | Development Environment |
| Kotlin / Java | Android App Development |
| Room Database | Offline Local Storage |
| MVVM Architecture | Clean Architecture Pattern |
| LiveData | Real-Time UI Updates |
| Intent API | WhatsApp / SMS Integration |
| GenAI Assistance | Development & Productivity Support |

---

## 📂 Project Architecture

```text
Grama-Khata/
│
├── app/
│   ├── activities/
│   ├── adapters/
│   ├── database/
│   ├── models/
│   ├── repository/
│   ├── viewmodel/
│   └── utils/
│
├── screenshots/
├── README.md
└── build.gradle
```

---

## 🔄 User Flow

### 1️⃣ Add Customer

- Enter customer details
- Add profile image

### 2️⃣ Record Transactions

- Press ➕ for credit
- Press ➖ for payment collection

### 3️⃣ View Due List

- Customers sorted by pending balance

### 4️⃣ Send Reminder

- Tap WhatsApp/SMS icon
- Reminder message opens automatically

---

## 🧠 Core Functionalities

### Real-Time Net Balance Calculation

The application instantly updates customer balance after every transaction using ViewModel and LiveData.

### WhatsApp Integration

Uses:

```kotlin
Intent.ACTION_SEND
```

to launch WhatsApp or SMS applications.

### Offline Data Integrity

Room Database ensures:

- Reliable local storage
- Fast access
- Data persistence

---

## 🎯 Impact Goals

### 🌐 Financial Digitization

Digitizing the unorganized rural credit system.

### 🏪 Support Small Retailers

Helping shopkeepers reduce financial confusion and improve recovery tracking.

### 🤝 Trust-Based Technology

Strengthening community trust through simple digital solutions.

---

## ✅ Success Criteria

- Instant balance updates after transactions
- Easy one-hand usability
- Daily collection report generation
- Offline functionality
- Simple and clean interface

---

## 📸 Screenshots

Add application screenshots here.

```text
screenshots/home.png
screenshots/customer.png
screenshots/dashboard.png
```

---

## 🔮 Future Enhancements

- Multi-language support
- Voice-based transaction entry
- AI-powered due prediction
- Cloud backup and synchronization
- UPI payment integration
- PDF report export

---

## 👨‍💻 Learning Outcomes

- Android App Development
- MVVM Architecture
- Room Database Integration
- Intent Handling
- Offline-First Application Design
- UI/UX for Rural Users
- Real-Time State Management

---

## 📜 License

This project is developed for educational and academic purposes.

---

## 🙌 Contributors

- Akshan B

---

## ⭐ GitHub Setup

### Clone Repository

```bash
git clone https://github.com/your-username/grama-khata.git
```

### Open Project

1. Open Android Studio
2. Select **Open Existing Project**
3. Choose the cloned folder

### Run the App

- Connect Android device or emulator
- Click ▶ Run

---

## 📬 Contact

For suggestions or collaboration:

- GitHub: your-github-profile
- Email: your-email@example.com
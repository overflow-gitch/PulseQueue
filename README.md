# 🏥 PulseQueue

PulseQueue is a real-time hospital queue management system that allows staff to manage patients and provides a public view of wait times.

---

## 🚀 Setup

1. Clone the repo:

```bash
git clone <repo-url>
cd PulseQueue-1
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the root and add:

```env
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
```

4. Run the app:

```bash
npm run dev
```

---

## ⚠️ Note

* `.env` is not included for security reasons
* Use `.env.example` as a reference
* Contact the team for Firebase config or use your own project

---

## 🛠️ Tech Stack

* React (Vite)
* Firebase (Auth + Firestore)

---

## 🔐 Security

* Firebase config is stored using environment variables
* Only authenticated users can modify data  

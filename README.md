# 🗺️ Travel Diary App (Hackathon Prototype)

A mobile-first, offline-first, privacy-preserving travel diary that automatically tracks trips and detects your mode of transport.

---

## 🔴 The Problem

In today's world of frequent travel, existing applications for tracking journeys fall short:
* **Manual & Tedious:** Users must manually log trips, and self-reported transport modes are often inaccurate.
* **Siloed Focus:** Apps like Google Maps Timeline focus on navigation, while fitness apps like Strava ignore transport context.
* **Connectivity Dependent:** Most apps require a constant internet connection, making them unreliable in low-connectivity areas.
* **Lack of Insight:** There's no easy way to analyze past trips, track your carbon footprint, or export data for personal use (like expense claims).

---

## 🎯 Our Solution

We've built a **holistic personal travel diary** that addresses these gaps. Our app:
* **Auto-tracks** trips using phone sensors (GPS, Accelerometer).
* **Intelligently detects** transport modes (walk, cycle, car, bus).
* Works **offline-first**, syncing to the cloud only when a network is available.
* Provides a rich **history dashboard** with analytics on mileage, time spent, and carbon savings.
* Respects user **privacy** with local-first data storage.

---

## ✨ Key Features

* 🤖 **Automatic Trip Detection:** No manual start/stop needed. The app works silently in the background.
* 🚶‍♂️🚗🚲 **Smart Mode Detection:** Uses multi-sensor fusion to accurately determine your mode of transport.
* 📴 **Offline-First Storage:** All your trips are saved locally on your device, making the app fully functional without an internet connection.
* 📊 **Analytics Dashboard:** Visualize your travel patterns with stats on mileage, average speed, and time spent per mode.
* 🌱 **Carbon Footprint Calculator:** See the positive impact of your eco-friendly travel choices (walking/cycling).
* 📄 **Export & Share:** Generate trip summaries in CSV/PDF format for insurance, expenses, or health tracking.
* 🛡️ **Privacy-First Approach:** Your data is yours. It stays on your device unless you explicitly choose to back it up.
* 🏆 **Gamification (Future Scope):** Earn badges and rewards for eco-friendly travel and achieving personal goals.

---

## 🚀 Live Showcase

You can view a static, visual prototype of the app's pages and features at the following link:

**[➡️ View the Live Demo Here](https://your-deployment-link.com)** *(Replace this with the link after you deploy the `index.html` file.)*

---



---

## 🛠️ Tech Stack

* **Frontend (Mobile):** Expo (React Native)
* **Routing:** Expo Router
* **Local Database:** SQLite (`expo-sqlite`)
* **Maps & Visualization:** `react-native-maps`
* **Backend (Optional):** Firebase / Supabase for auth and cloud sync.
* **Showcase Prototype:** HTML & CSS

---

## ⚙️ Getting Started (Running the Full App)

To run the full React Native application on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/travel-diary-app.git](https://github.com/your-username/travel-diary-app.git)
    cd travel-diary-app
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the application:**
    ```bash
    npx expo start
    ```
    This will open the Metro Bundler. You can then scan the QR code with the Expo Go app on your iOS or Android device.

---

## 🔮 Future Scope

* **Public Transport API Integration:** Suggest missed bus/metro trips based on location history.
* **AI Assistant:** Provide personalized suggestions for more eco-friendly travel alternatives.
* **Community Dashboards:** Allow companies or groups to track their collective carbon savings.
* **AR/VR Journaling:** Enable immersive playback of past trips.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🧑‍💻 Built By

* [Prabhugari Vihari] - [[Link to your GitHub/LinkedIn]](https://github.com/VIHARI1106)

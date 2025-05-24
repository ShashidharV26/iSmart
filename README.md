# iSmart

## 🎬 Overview

**iSmart** is an **OTT Android TV application** designed to deliver entertainment content to passengers in traveler buses. Each seat has an Android device where **iSmart** is set as the default launcher. The app provides a rich mix of local and online content — including Movies, Cartoons, Comedy, YouTube videos, OTT Play integration, and Games — ensuring passengers enjoy uninterrupted entertainment even in remote areas.

Content is distributed via a **local bus server** setup and automatically updates when the device gains internet access. The app includes intelligent features like holiday greetings, operator messages, ads, content tracking, and server-side load balancing for optimal streaming.

---

## 🚀 Features

### 📡 Bus Device and Server Setup
- Each bus contains **multiple local servers** (3 per bus).
- A **default server** syncs with the cloud server when online.
- Devices use load balancing and connect to the optimal server.
- Automatic fallback to alternative server when default is overloaded.

### 📥 Content Fetching and User Flow
- On boot, devices connect to a server and fetch updated content.
- First-time user interaction triggers an **introductory operator video**.
- Post-intro, app navigates to **home screen** with categorized content.

### 🏠 Home Screen Interface
- Tabs for categories: Movies, Cartoons, Comedy, Games, OTT Platforms, etc.
- Latest content carousel pulled from local server.
- Integrated **YouTube APIs** for live content when online.

### ▶️ Media Playback
- Displays a **wishing banner** and **holiday wishes** before playing content.
- Plays ads between movies and music videos.
- Ads are managed from the cloud and synced when internet is available.

### 🎮 Games and Extras
- Integrated with third-party APIs for offline/online games.
- Bluetooth pairing and safety info features built-in.
- Collects daily user interaction data (e.g., selected content, ad views).

### 🧠 Data Collection and Sync
- Stores user interaction locally per day.
- Server pulls data from all devices daily and pushes to cloud.

---

## 🛠 Tech Stack

| Area                     | Tech Used                        |
|--------------------------|----------------------------------|
| Language                 | Java + Kotlin                    |
| UI Design                | XML + Material 3 Design          |
| Architecture             | MVVM                             |
| API Communication        | Retrofit 2                       |
| Media Playback           | Media3                           |
| Crash Reporting          | Firebase Crashlytics             |
| Local Storage            | Room Database                    |
| UI Components            | Jetpack Presenters               |
| YouTube Integration      | YouTube APIs                     |
| Ads                      | Custom Video Ad Player           |
| Dialogs                  | Custom Fragment Dialogs          |

---

## 🧩 Development Contributions

- ✅ Migrated project from **Java-only to Java + Kotlin**.
- ✅ Revamped the entire UI using **Material 3 Design**.
- ✅ Integrated **Firebase Crashlytics** for real-time crash monitoring.
- ✅ Replaced SQLite with **Room Database** for efficient local storage.
- ✅ Implemented **server-side load balancing logic** for better performance.
- ✅ Integrated **YouTube APIs** to enrich available content.
- ✅ Performed multiple **code optimizations** for improved performance and stability.

---

## 🏆 Achievements

- ✨ **New UI design** increased user engagement and satisfaction.
- 📺 **YouTube API integration** improved screen time and reduced dependency on external apps.
- 🛠 **Crashlytics monitoring** enabled faster bug resolution and better user experience.
- 🔧 Kotlin integration reduced boilerplate code and enhanced maintainability.

---

## 📸 Screenshots

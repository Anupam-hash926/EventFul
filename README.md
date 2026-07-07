<div align="center">

```text
███████╗██╗   ██╗███████╗███╗   ██╗████████╗███████╗██╗   ██╗██╗
██╔════╝██║   ██║██╔════╝████╗  ██║╚══██╔══╝██╔════╝██║   ██║██║
█████╗  ██║   ██║█████╗  ██╔██╗ ██║   ██║   █████╗  ██║   ██║██║
██╔══╝  ╚██╗ ██╔╝██╔══╝  ██║╚██╗██║   ██║   ██╔══╝  ██║   ██║██║
███████╗ ╚████╔╝ ███████╗██║ ╚████║   ██║   ██║     ╚██████╔╝███████╗
╚══════╝  ╚═══╝  ╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚═╝      ╚═════╝ ╚══════╝
```

### **Eventful** - *Discover, connect, and engage with your local world*

> ⚠️ **Note on Repository Contents:** Due to a hardware migration, the original source code for this project was lost. This repository serves as a portfolio piece detailing the app's architecture and features. The compiled Android release (`app-release.apk`) is included in this repository for live demonstration.

---

## What is Eventful?

Finding local events that actually match your interests can be overwhelming. **Eventful** is a robust, location-aware mobile application designed to seamlessly bridge the gap between local happenings and user preferences.

Built with a focus on intuitive UI/UX, Eventful learns from your profile to provide a personalized dashboard highlighting "Upcoming Events Near You" and "Tailored For You" recommendations. Whether you prefer browsing through hierarchical categories or exploring geographical map pins, Eventful makes discovering your next professional networking meetup or local music concert effortless.

> *"More than a directory - a personalized local experience."*

---

## Features

| Feature | Description |
| --- | --- |
| 🔐 **Secure Authentication** | Integrated Email/Password login and new user registration flow. |
| 🎨 **Personalized Dashboard** | A dynamic home screen displaying customized "Upcoming Events" and "Tailored For You" sections based on user profiles. |
| 🗺️ **Interactive Mapping** | Location-based discovery showing events as geographical pins via map integration. |
| 📂 **Hierarchical Filtering** | Explore events categorized by type (Academic, Professional, Social) with sub-categories (Career Fairs, Job Meetups) for efficient browsing. |
| 👤 **Profile Management** | View account details, manage active registrations in "My Events", and edit personalized interests to refine recommendations. |
| 🌙 **Modern UI/UX** | Clean navigation drawer, glassmorphism search bars, and an integrated Dark Mode toggle for user accessibility. |

---

## Getting Started (Testing the App)

Because this repository houses the compiled release rather than the raw source code, you can easily test the application by "sideloading" it onto any Android device.

### 1. Download the APK

Download the `app-release.apk` file directly from this repository to your Android smartphone.

### 2. Allow Installation from Unknown Sources

By default, Android devices restrict the installation of applications outside of the Google Play Store.

1. Open the downloaded `.apk` file.
2. If prompted by a security popup, tap **Settings**.
3. Toggle on **Allow from this source** (for your browser or file manager).
4. Tap the back arrow.

### 3. Install and Explore

1. Tap **Install** on the prompt.
2. Open the **Eventful** app from your home screen.
3. Create a test account to explore the dashboard, map features, and event filtering.

---

## Tech Stack

| Layer | Technology |
| --- | --- |
| **Frontend Framework** | Flutter - Cross-platform UI toolkit |
| **Language** | Dart |
| **Backend & Database** | Firebase (Authentication & Data Storage) |
| **Mapping Service** | OpenStreetMap (OSM) via `flutter_map` |
| **Location & Math** | `latlong2` & Google Play Services |

---

Built for Mobile Application Development coursework · Ramaiah Institute of Technology

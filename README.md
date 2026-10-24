#  Car Diary - Dealer Inventory & Dashboard App

Car Diary is a high-performance, offline-first Android mobile application built specifically for used car dealerships. It bridges a modern HTML5/CSS3/JavaScript frontend with native Android components via a custom WebView architecture, allowing dealers to manage vehicle stock, track profit margins, and instantly share listings to WhatsApp.

---

## Key Features

* Offline-First SQLite Storage: Fast and secure local data persistence using embedded SQLite and JSON serialization.
* Direct WhatsApp Multi-Media Sharing: Exports formatted vehicle details along with multiple compressed photos directly via native Android `Intent.ACTION_SEND_MULTIPLE`.
* Dynamic Deal Tracking: Automatically calculates profit, loss, or break-even status when a car is marked as sold, complete with buyer details and agreement photo archives.
* Custom Radio Fuel Selection: Supports Petrol, Diesel, CNG, Petrol + CNG, EV, and Hybrid vehicle variants.
* Optimized Mobile UX: Tailored input handling and WebView background matching to ensure smooth performance across tall-screen Android devices without UI layout glitches.

---

##  Tech Stack & Architecture

* Frontend: HTML5, CSS3, JavaScript (Vanilla UI, dynamic DOM rendering).
* Native Android Layer: Java, `WebView`, `WebAppInterface`, SQLite (`DatabaseHelper`).
* Intents & File Sharing: `FileProvider`, `ContentProvider`, Camera/Gallery Media Store integration.

---

##  Getting Started

1. Download the `CarDiary.zip` file from this repository and extract it.
2. Open the project in Android Studio.
3. Sync Gradle and build the project or generate an APK to run it on your physical Android device.

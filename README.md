**🗺️ Sarathi Maps & Navigation** 

---

# 🚗 Sarathi Maps & Navigation

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter" />
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green" />
  <img src="https://img.shields.io/badge/Google%20Maps-Enabled-red?logo=google-maps" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

---

## 📌 About the Project

**Sarathi Maps & Navigation** is a Flutter-based cross-platform mobile application that provides real-time location tracking, place search, custom markers, and interactive map visualization using the Google Maps SDK. The app delivers a smooth, Google Maps–like user experience with clean UI and animated camera movements.

---

## ✨ Features

* 🗺 **Google Maps Integration**
  Interactive map with zoom, tilt, bearing, and smooth camera animations.

* 📍 **Current Location Tracking**
  Displays the user’s current position with an **orange active marker**, similar to Google Maps.

* 🔍 **Search Location by Name**
  Search any city, area, or place and instantly navigate to it.

* 🟠 **Single Active Location Marker**
  Ensures only one orange marker is visible at a time (search or current location).

* 🟢 **Custom Static Markers**
  Loads predefined markers from local JSON assets.

* 🌗 **Dark & Light Map Themes**
  Toggle map styles for better visibility and accessibility.

* 🎯 **Smooth Camera Animations**
  Polished transitions for a professional navigation experience.

* 📱 **Cross-Platform Support**
  Works seamlessly on **Android** and **iOS** using a single Flutter codebase.

* 🔐 **Runtime Location Permission Handling**
  Handles location permissions correctly following platform guidelines.

* 🧩 **Modular & Scalable Architecture**
  Clean separation of UI, location services, and data layers.

---

## 📸 Screenshots


<img width="1470" height="956" alt="Screenshot 2025-12-17 at 11 48 52 PM" src="https://github.com/user-attachments/assets/24c0010c-0f7b-4068-bc2a-3f0493ed9f87" />

<img width="1470" height="956" alt="Screenshot 2025-12-17 at 11 48 22 PM" src="https://github.com/user-attachments/assets/867a6d54-773f-47f5-a54c-55d85cb7ffbe" />


<img width="1470" height="956" alt="Screenshot 2025-12-17 at 11 47 25 PM" src="https://github.com/user-attachments/assets/3b5feb13-9772-4ffc-84be-a26e7e361786" />
<img width="1470" height="956" alt="Screenshot 2025-12-17 at 11 48 25 PM" src="https://github.com/user-attachments/assets/22d386f4-9d95-4c5d-b320-6d99efc26ce1" />


## 🏗 System Architecture



<img width="666" height="504" alt="PP71JiCm38RlUGgh1mI7lG9QrOvfi6v8eUB2nSgiB2ABgyH3cX3lJaFAsCIXglF7d_p_pZm9HZaUl18dda1ZHDaxw718S0CR_70MnN606UXJ4Zf07StU2HavHb8AZN24Fb5KQa3pZfQWUl174OfG3qC5dmh0y67WG46WwbUmnXF5jt3xwdQM9C_H9XA5T5S19kXNryJe1HeE4jdx7sx9R3sDyfzQoAwv9jTiYlaE0zh24lki" src="https://github.com/user-attachments/assets/be920b16-1553-4302-bf8a-012dd0387b57" />


### 🔄 Location Flow Diagram (PlantUML)

<img width="480" height="364" alt="NP3FIiGm4CRlUOfX3tlR5_0WAs8NOSiMqGSOqeyQJ3CncIg-lPEo2jrJo_Vx_eGvLkMYonoT1esWitZM88awg7-dFVLSFb3eBO-ie2xAjtFiLKogA2vRElYGEIdjkhYeDlFpZhZQPujFaDZgfQpuz7IvuI9JX2tckXhwXy6vjaA7UokZEthbJFtF_oETYOQioDWBFXTKfG5b3hKstC3XBtksY2uZQ6_vDAt_rm8RCaClNw17" src="https://github.com/user-attachments/assets/8cff375b-048d-46e4-8900-190d400cca52" />



---

## 🧰 Tech Stack

| Layer     | Technology              |
| --------- | ----------------------- |
| Language  | Dart                    |
| Framework | Flutter                 |
| Maps      | Google Maps Flutter SDK |
| Location  | Geolocator              |
| Search    | Geocoding               |
| UI        | Material 3              |
| Platforms | Android, iOS            |

---

## 📂 Project Structure

```text
sarathi/
├── android/
├── ios/
├── lib/
│   ├── main.dart
│   └── src/locations.dart
├── assets/
│   └── locations.json
├── screenshots/
├── pubspec.yaml
└── README.md
```

---

## ⚙️ Setup & Run

```bash
flutter pub get
flutter run
```

---

## 🍎 iOS Permission Configuration

Add the following to `ios/Runner/Info.plist`:

```xml
<key>NSLocationWhenInUseUsageDescription</key>
<string>Sarathi needs your location to show your position on the map.</string>
```

---

## ⚠️ Simulator Note

* iOS Simulator uses **simulated GPS**
* Set correct location via:
  `Features → Location → Custom Location`

---

## 🚀 Future Enhancements

* 🛣 Turn-by-turn navigation with polylines
* 📏 Distance and ETA calculation
* 🔵 Google Maps blue dot with accuracy radius
* 🔍 Places autocomplete
* 📶 Offline map support

---




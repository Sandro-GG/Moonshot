# 🌙 Moonshot

**Moonshot** is a SwiftUI-based app that showcases the Apollo space missions in a visually engaging and educational way. Built as part of the "100 Days of SwiftUI" course, this project demonstrates how to decode JSON, create reusable views, and build clean navigation flows using SwiftUI.

---

## 🚀 Features

- Loads Apollo mission and astronaut data from bundled JSON files  
- Clean grid layout of missions with images and launch dates  
- Detail views with astronaut bios and mission highlights  
- Responsive layout for various screen sizes  
- Navigation using `NavigationStack`

---

## 📁 Project Structure

- `ContentView.swift` – Main screen with a grid of missions
- `MissionView.swift` – Detail screen for each mission
- `AstronautView.swift` – View for each astronaut's profile
- `Astronaut.swift` – Codable model for astronaut data
- `Mission.swift` – Codable model for mission data
- `astronauts.json` – Static JSON file with astronaut info
- `missions.json` – Static JSON file with mission info
- `Bundle-Decodable.swift` – Utility to decode local JSON

---

## ✅ Key Concepts

- Codable for JSON decoding  
- GeometryReader for adaptive layout  
- NavigationStack for programmatic navigation  
- LazyVGrid for grid-based layout  
- ScrollView and custom styling in SwiftUI

---

## 🛣 Future Improvements

- Add search functionality  
- Add favorites/bookmark feature  
- Support for dark mode & dynamic type  
- Local notifications for mission dates  

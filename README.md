NutriTrack – Simple Calorie & Water Tracker (SwiftUI)

NutriTrack is a simple iOS application created as part of my challenge project.  
The goal of this app is to help users track their daily calorie intake and water consumption in an easy and clean interface.

This project was mainly focused on understanding how SwiftUI works, especially how views update automatically when the user enters new data.

 Why I Chose This App
During my research, I became very interested in apps that update their UI live based on user input.  
Hydration and calorie-tracking apps were great examples of this, and I noticed how popular the YAZIO app is.  

I wanted to recreate a simplified version of this idea to learn:

- How to build a clean UI in SwiftUI  
- How to make values update automatically  
- How navigation and tab bars work  
- How to structure multiple pages inside one app  

Features of the App (Current)
1. Water Tracking Page
- User can manually enter how much water they drink (in ml)
- Total daily water amount updates automatically
- Clean, simple layout

2. Calorie Tracking Page
- User can add calories manually
- Daily calorie total updates immediately

3. Basic Tab Bar Navigation
- Tabs for **Calories**, **Water**, and **Steps**

4. “Steps” Page (Future Implementation)
- The page exists inside the app
- Displays *“Coming Soon”*
- Will count daily steps once implemented

---

Future Improvements
If I have more time, I plan to add:

- Apple HealthKit integration (for step tracking)
- Daily goals + progress rings
- Custom user goals (water + calorie targets)
- Saving daily data locally
- Cleaner design system + reusable components


What’s Included in This Repository
This repo contains:

- `/NutriTrack.xcodeproj` – the main Xcode project  
- `/Sources/*.swift` – SwiftUI views and logic  
- `/Assets.xcassets` – app icon, colors, and images  
- `README.md` – (this file) project documentation  
- Optional: design or analysis files (if added)  

App Inspiration
The primary inspiration was the **YAZIO** app (available on the App Store),  
but NutriTrack is built from scratch as a simple and beginner-friendly version.

---

## 🙋‍♂️ Author
This project was created as part of my learning journey in iOS development.  
My main goal was to understand SwiftUI state updates, interface structure,  
and how to build a functional multi-page app from scratch.


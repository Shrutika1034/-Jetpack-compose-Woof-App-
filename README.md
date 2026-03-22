#  Woof App (Jetpack Compose)

A modern Android application built using **Kotlin** and **Jetpack Compose** that displays a list of dogs with images, names, and descriptions. The app demonstrates clean UI design, animations, and state management.

---

##  Overview

The Woof App showcases how to build a **dynamic and interactive UI** using Jetpack Compose.  
Users can browse a list of dogs and expand each item to view more details.

---

##  Features

-  Display list of dogs with images  
-  Expandable cards to show additional details  
-  Material 3 modern UI design  
-  Smooth animations using Compose  
-  State-driven UI updates  

---

##  Tech Stack

- **Kotlin**
- **Jetpack Compose**
- **Material 3**
- **Android Studio**

---

##  Concepts Used

- Composable functions  
- State management (`remember`, `mutableStateOf`)  
- LazyColumn for list rendering  
- Animation APIs in Compose  
- Material 3 theming  

---

##  Project Structure

Woff App structure 


Woof/                               
│
├── app/                            
│   │
│   ├── src/
│   │   ├── main/                   
│   │   │
│   │   ├── java/com/example/woof/  
│   │   │   │
│   │   │   ├── MainActivity.kt     → Builds UI, manages state, animation, and user interaction
│   │   │   │
│   │   │   ├── data/               → Data layer package
│   │   │   │   └── Dog.kt          → Defines Dog data model and provides dog list
│   │   │   │
│   │   │   └── ui/theme/           → Design system package
│   │   │       ├── Theme.kt        → Applies global Material 3 theme
│   │   │       ├── Color.kt        → Defines app color palette
│   │   │       ├── Shape.kt        → Defines rounded corner shapes
│   │   │       └── Type.kt         → Defines typography styles (fonts & text sizes)
│   │   │
│   │   ├── res/                   
│   │   │   │
│   │   │   ├── drawable/           → Stores images and vector graphics
│   │   │   │   ├── dog1.png        → Dog image displayed in list
│   │   │   │   ├── dog2.png        → Dog image displayed in list
│   │   │   │   ├── dog3.png        → Dog image displayed in list
│   │   │   │   ├── dog4.png        → Dog image displayed in list
│   │   │   │   └── ic_woof_logo.xml → Vector paw logo used in TopAppBar
│   │   │   │
│   │   │   ├── mipmap/             
│   │   │   │   ├── ic_launcher.png 
│   │   │   │   └── ic_launcher_round.png 
│   │   │   │
│   │   │   └── values/             
│   │   │       ├── strings.xml     → Stores all text content
│   │   │       ├── dimens.xml      → Stores reusable spacing and size values
│   │   │       ├── colors.xml      → Default color resources (auto-generated)
│   │   │       └── themes.xml      → App theme configuration (XML-based)
│   │   │
│   │   └── AndroidManifest.xml    
│   │
│   └── build.gradle.kts            → Module-level dependencies and build configuration
│
└── build.gradle.kts               



---

##  How to Run

### 🔧 Requirements
- Android Studio installed
- Android Emulator or physical device

###  Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Shrutika1034/-Jetpack-compose-Woof-App-.git

2. Open the project in Android Studio
3. Wait for Gradle Sync to complete
4. Run the app:
   Click  Run
   Select emulator or device

# WorkManagerExample 🚀

A hands-on Android project demonstrating the use of **WorkManager** for background tasks.

![Android](https://img.shields.io/badge/Android-green?style=flat-square)
![Kotlin](https://img.shields.io/badge/Kotlin-blue?style=flat-square)
![WorkManager](https://img.shields.io/badge/WorkManager-orange?style=flat-square)

---

## 📖 Description
This project is an exercise to explore the capabilities of **WorkManager** in Android.  
WorkManager is a powerful library for managing deferrable and guaranteed background tasks, even if the app is closed or the device restarts.

### Features:
- ✅ One-time tasks  
- ✅ Periodic tasks  
- ✅ Chained tasks  
- ✅ Task constraints (e.g., network, charging)  

---

## 📦 Dependencies
This project uses the following dependencies, managed via `libs.versions.toml`:

```toml
[versions]
agp = "8.3.0"
kotlin = "1.9.0"
coreKtx = "1.15.0"
junit = "4.13.2"
junitVersion = "1.1.5"
espressoCore = "3.5.1"
lifecycleRuntimeKtx = "2.8.7"
activityCompose = "1.8.0"
composeBom = "2024.04.01"
work = "2.9.0"

[libraries]
#...
androidx-lifecycle-runtime-ktx = { group = "androidx.lifecycle", name = "lifecycle-runtime-ktx", version.ref = "lifecycleRuntimeKtx" }
androidx-lifecycle-viewmodel-ktx = { group = "androidx.lifecycle", name = "lifecycle-viewmodel-ktx", version.ref = "lifecycleRuntimeKtx" }
androidx-lifecycle-runtime-compose = { group = "androidx.lifecycle", name = "lifecycle-runtime-compose", version.ref = "lifecycleRuntimeKtx" }
androidx-work-runtime = { group = "androidx.work", name = "work-runtime-ktx", version.ref = "work" }
#...
```

📂 You can view the full `libs.versions.toml` file [here](https://github.com/fekri8614/android-worker/blob/master/gradle/libs.versions.toml).

---

## 🛠️ Setup

To run this project your own, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/fekri8614/android-worker.git
   ```
2. Open the project in **Android Studio**.
3. Sync the project with Gradle files.
4. Build and run the app on an emulator or physical device.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature/YourFeatureName
   ```
3. Commit your changes:
   ```sh
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature/YourFeatureName
   ```
5. Open a **Pull Request**.

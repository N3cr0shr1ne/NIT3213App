NIT3213 Android Application – Assignment 2
This Android application was created for Assignment 2 in the NIT3213 unit at Victoria University.
It demonstrates modern development practices using the Gradle build system, enabling efficient project setup, dependency handling, and build configuration.

1. Overview of Features
Note: Specific app functionalities were not included in the submitted files. Please update this section with actual feature details if available.

1.1 User Login Functionality (if applicable)
1.2 Main Dashboard to display data
1.3 Detail View Screen for in-depth content
1.4 Logout and seamless navigation support

2. Development Architecture
This assumes standard architecture used in contemporary Android apps. Please revise if your structure differs.

MVVM (Model-View-ViewModel) for organized separation of concerns

Hilt for dependency management

Retrofit for handling REST API communication

LiveData and ViewModel for lifecycle-aware data handling

ViewBinding for type-safe access to UI elements

3. Suggested Project Layout
css
Copy
Edit
com.example.yourapp
├── data
│   ├── api
│   ├── model
│   └── repository
├── di
├── ui
│   ├── login
│   ├── dashboard
│   └── details
├── utils
├── MainActivity.kt
└── MainApplication.kt
4. Build Configuration & Key Dependencies
Written in Kotlin

Uses Gradle as the build automation tool

AndroidX libraries enabled for enhanced compatibility

Kotlin style set to follow the “official” convention

Reduced R class size with non-transitive settings

Important Configuration Snippets
properties
Copy
Edit
// gradle.properties
org.gradle.jvmargs=-Xmx2048m -Dfile.encoding=UTF-8
android.useAndroidX=true
kotlin.code.style=official
android.nonTransitiveRClass=true
properties
Copy
Edit
// local.properties (auto-generated for local setup)
sdk.dir=C:\\Users\\sushr\\AppData\\Local\\Android\\Sdk
Note: Sensitive or system-specific files like local.properties and IDE-related folders are excluded from version control using .gitignore.

5. Running the Application
Launch Android Studio and open the project directory.

Ensure the Android SDK path is correctly set (local.properties).

Sync and build the project using Gradle.

Connect a device or start an emulator.

Run the application directly from the IDE.

6. Version Control Practices
The .gitignore file is configured to exclude:

IDE-specific folders (.idea/)

Local build output (/build/)

System-specific settings (local.properties)

Gradle-related caches and native build directories

7. License
This application was developed exclusively for academic use in the NIT3213 unit at Victoria University.
Use of this project is restricted to educational and demonstration purposes only.

8. Developer Information
Name: Sushrit Phuyal
Student ID: s8114214

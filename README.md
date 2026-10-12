# MobileApp
Hello everyone!

Today, I am going to present my Android application called **TaskMate – Your Daily Task Companion**.

My application is developed using Android Studio, Java, and XML.

First, we have the **Splash Screen Activity**. It displays the TaskMate title on a blue background with the subtitle “Your Daily Task Companion.” After two seconds, it automatically navigates to the login screen.

Second, we have the **Login Screen Activity**. It contains the TaskMate heading, a welcome message, a Google sign-in button, email and password fields, a Login button, and a Sign Up button.

I have used **LinearLayout** in my XML files. The vertical orientation arranges the interface elements from top to bottom. I have used TextView for text, EditText for user input, and Button for user interaction.

When the user clicks the Google sign-in button, the app attempts to open the Google account selection screen. Firebase Authentication must be configured to complete the sign-in process.

When the user clicks the Sign Up button, the app opens another activity that displays a blank white screen.

Finally, this project demonstrates Android activities, XML layouts, user interface design, button click events, and activity navigation.

Thank you!


**APP Included:**

**Activity 1: Splash Screen**
- Blue background.
- TaskMate title and subtitle.
- Opens the login screen automatically after two seconds.
- Files: SplashActivity.java and activity_splash.xml.
**  
Activity 2: Login Screen**
- Google sign-in button.
- Email and password fields.
- Login button.
- Sign Up button.
- Files: LoginActivity.java and activity_login.xml.

**Activity 3: Sign-Up Screen**
- Opens when you click Sign Up.
- Displays a blank white screen, as requested.
- Files: SignUpActivity.java and activity_signup.xml.


**Layout USE:**

You used LinearLayout in both the splash and login screens.
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <!-- Add TextViews, EditTexts and Buttons here -->

</LinearLayout>

- LinearLayout: arranges interface elements in a row or column.
- android:orientation="vertical": places elements from top to bottom.
- TextView: displays text.
- EditText: accepts user input.
- Button: performs an action when clicked.
**  Google Sign in Button Work:**
The project includes Google Sign-In and Firebase Authentication code.
When you click SIGN IN WITH GOOGLE, it attempts to open the Google account chooser. To make the authentication work, you must first:
1. Create a Firebase project.
2. Register your Android app with package name com.example.taskmate.
3. Put your downloaded google-services.json file inside the project's app folder.
4. Enable Google in Firebase Authentication.
5. Configure your app's SHA-1 fingerprint.
Important: Google authentication cannot complete until this setup is done. The regular email/password Login button currently performs basic input validation; it is not connected to an authentication service yet.

** Upload the project to GitHub**
1. Extract TaskMate_Android_Project.zip.
2. Open the extracted project in Android Studio.
3. Complete the Firebase setup if you want to test Google sign-in.
4. Run the app and test all three screens.
5. Create a new repository on GitHub.
6. Upload the project files and include the README.

Suggested repository name: TaskMate-Android-App
One final note:
"the ZIP contains the project source and configuration, but I haven't run an Android Gradle build here. Open it in Android Studio and resolve any version or SDK compatibility prompts before publishing it."

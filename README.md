# fingerprint-secured-android-notes

## What is a Fingerprint Secured Android Notes?
This app helps the user to make android notes with Fingerprint security. This doesn’t require login or signup. It requires fingerprint authentication to unlock. So only the owner of the device can unlock it.

## The flow of the Application
The first screen is the finger authentication screen. You can not enter into the app without giving FingerPrint.
Dashboard Screen

The dashboard screen shows all the notes created. To create a new note click on the + button at the bottom. The app will take you to the Add note screen.

## Add Note Screen
On this screen, enter the title and the description of the note. Click on the Save button at the top. Your note will be saved and you can see it in the dashboard. You can also delete them by clicking the delete button at the top or by right-swiping on the note.

## Features of the Fingerprint Secured Android Notes App
1. Only users which have fingerprint security in their phones can use this application.
2. No one can access your notes without your fingerprint.
3. You can create a new note.
4. You can update an already created note.
5. You can delete the note by right-swiping on the note and can also undo the task within 5 sec.
6. You can also delete all the notes at once by clicking on the delete button at top.
7. This is an offline application.

## Project Prerequisites
You should have a fair idea of how the note-taking application works. The project requires you to have good knowledge of the following technologies/tools.

1. Java: Java is a programming language. We will use this for the logic in our application.

2. XML: XML is a designing language.

3. Android Studio: It offers some pre-built tools for building apps faster.

4. SQLite database: We will use SQLite’s in-built database. Android has its own database. You should also be familiar with SQL queries.

5. Authentication with fingerprints in Android: The fingerprint library for Android. See the android documentation for this library.

6. Themes: This file defines the theme of our app.

7. Colors: This file will contain all of the colors used in the app.

## Developing the DataFlair Fingerprint Secured Android Notes App
Ok, so before getting to implement the fingerprint-secured android notes app, we’ll understand the files that we have created for this application. Let us see them one by one-

1. It will contain the code for the UI screen of our Fingerprint. The first file is activity_fingerprint.xml. In this file, the user authenticates by using his fingerprint.

2. The second file is FingerprintActivity.java, which contains the logic for our fingerprint screen.

3. The third file is activity_dashboard.xml, which contains the UI code of our dashboard. Here, we will display all of the user’s notes.

4. DashboardActivity.java is the next file and contains the code for the previous file.

5. Then we have files to handle the UI and logic part of our Add note and update notes activity.

6. There is one class databaseClass.java. This class is to connect to SQLite database and will have the queries to fetch all notes, add a new note, update old notes and delete all notes.

7. Color.xml – This file has all the colors that we have used in our application.

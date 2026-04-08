Music Playlist Manager App
 Project Overview
   The Music Playlist Manager App is an Android application developed using Android Studio and Java. The application allows users to create and manage playlists by adding, removing, and sorting songs. It demonstrates the use of Android components, list management, and local data storage.

Team Members
  1.Brinda B

  2.N Kavyashree 

  3.Yashaswini K

Objectives
          1.To develop an Android application using Java

          2.To implement playlist and song management

          3.To use ListView for displaying data

          4.To implement local storage using SharedPreferences

Features
       1.Create playlists

       2.Add songs to playlists

       3.Remove songs using long press

       4.Sort songs alphabetically

       5.Persistent storage of data
Technologies Used
         1. Android Studio

         2.Java

         3.XML

         4.SharedPreferences

        5.Gson Library

Application Structure
        MainActivity
                Displays the list of playlists and provides an option to create a new playlist.

        CreatePlaylistActivity
                Allows the user to enter and save a playlist name.

          PlaylistDetailActivity
                  Allows users to add, remove, and sort songs within a playlist.

Project Structure
MusicPlaylistManager
│
├── app
│ ├── src/main/java/com/example/musicplaylistmanager
│ │ ├── MainActivity.java
│ │ ├── CreatePlaylistActivity.java
│ │ ├── PlaylistDetailActivity.java
│ │ └── Playlist.java
│ │
│ ├── res/layout
│ │ ├── activity_main.xml
│ │ ├── activity_create_playlist.xml
│ │ └── activity_playlist_detail.xml
│ │
│ └── AndroidManifest.xml

How to Run the Application
         Using Emulator
         Open the project in Android Studio

        Create or select a virtual device

         Run the application

          Using Android Device
          Enable Developer Options

           Enable USB Debugging

            Connect the device

            Run the application

Expected Outcome
         The application allows users to manage playlists and songs efficiently. Data is stored locally and remains available even after restarting the application.

Conclusion
           This project demonstrates the implementation of an Android application using Java, focusing on list management and local storage. It provides a simple and effective solution for managing playlists.

Additional Resources
         Code output screenshots have been attached as a PDF document for reference.


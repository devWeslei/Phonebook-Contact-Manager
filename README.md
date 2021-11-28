# agenda_contatos
## Running
<p align="center">
  <img alt="Demo" src="https://github.com/devWeslei/Phonebook-Contact-Manager/blob/main/assets/demo.gif">
</p>   

## About this Project
A Phonebook contact manager project in Flutter.

## Some Observations about this App
-I had a issue starting the android emulator camera, the error was that the emulator was not allowed.

how to fix it: in the AndroidManifest.xml directory (android/app/debug/AndroidManifest.xml), I added the line:
  
`<uses-permission android:name="android.permission.QUERY_ALL_PACKAGES"/>`

## Functionalities
-Singleton pattern.   
-local database with SQFlite.

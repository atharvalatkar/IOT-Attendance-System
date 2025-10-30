# IOT-Attendance-System
# Smart RFID Attendance System

# Summary
This is an IoT-based Attendance System built using an ESP8266 (NodeMCU) and an RFID module (MFRC522).
The system scans RFID cards (or any compatible NFC cards like a Metro card) and automatically records attendance data in a Google Sheet through Wi-Fi.
It’s a simple, low-cost way to manage attendance digitally.

# Components/Tools Used
1. ESP8266 (NodeMCU)
2. MFRC522 RFID Module
3. Metro Card (used instead of the RFID key/tag)
4. USB Cable for Programming
5. Arduino IDE
6. Google Sheets (for storing attendance)
7. Google Apps Script (for connecting ESP8266 to Google Sheets)
   
# Features
1. Works with Metro cards or any RFID card
2. Automatic attendance logging in Google Sheets
3. Wireless communication using Wi-Fi
4. Low-cost and easy to build
5. Beginner-friendly IoT project

# Output
Each time a card is scanned, a new entry appears in the Google Sheet containing:
1. Card UID(aka Student Name)
2. Date
3. Time


 

# Smart Wallet Card System for University of Baghdad
A secure, integrated digital payment and identification system designed to modernize campus operations.

🚀 Overview
The system addresses the limitations of traditional cash-based payments and manual ID checks at the University of Baghdad. It replaces legacy systems for bus fare collection and cafeteria transactions with a unified digital solution.

🛠️ Tech Stack
 * Frontend: FlutterFlow (Mobile Application).
 * Backend: Supabase (PostgreSQL, Auth, Database Services).
 * Hardware Integration: ESP32 Microcontrollers, NFC (PN532), and Ultrasonic Communication.

✨ Key Features (My Contribution)

As the Mobile Application Developer, I implemented:
 * Secure Authentication: User login using biometric (fingerprint) or PIN.
 * Real-time Balance Management: Instant balance display and recharge functionality via bank cards.
 * P2P Fund Transfer: Secure money transfer between students without fees.
 * Dual-Mode Payments: Support for contactless payments via NFC and Ultrasonic signaling.
 * Offline Operation: Payment initiation even without internet connectivity, with delayed cloud synchronization.

🏗️ System Architecture
The system utilizes a central /update endpoint that verifies credentials and updates balances across both local and cloud servers. This ensures operational continuity even during internet outages.

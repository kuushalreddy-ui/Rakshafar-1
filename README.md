# Rakshafar
🛡️ Rakshafar – Your Travels Savior

Rakshafar is a smart travel safety application designed to protect tourists and citizens by combining real-time geo-fencing, emergency location sharing, and SOS alerting features.
The app detects when users enter dangerous or restricted zones, automatically triggers alerts, and enables instant SOS communication during emergencies.

🚀 Key Features
🗺️ 1. Geo-Fencing Dangerous Areas

Automatically identifies and marks unsafe or high-risk zones (e.g., crime-prone, accident-prone, or restricted areas).

Alerts users when they enter or approach a dangerous zone using notifications or sound alerts.

Uses real-time GPS tracking and predefined coordinates from an admin or database.

Can dynamically update unsafe zones from a server or external dataset.

📍 2. Location Sharing During Emergencies

Enables users to share their live location with trusted contacts or authorities during an emergency.

Location is shared via SMS, WhatsApp, or email (depending on permissions).

Tracks the user’s position continuously until the situation is marked as resolved.

Ideal for solo travelers, field workers, and tourists in unfamiliar areas.

🚨 3. SOS (Emergency) Feature

A one-tap SOS button triggers an instant distress signal.

Sends user’s live coordinates, device info, and timestamp to pre-set emergency contacts or control centers.

Works even in low-network situations using SMS fallback.

Optional sound alarm or vibration pattern to attract nearby attention.

🧠 How It Works

User Registration:
The user registers and grants necessary permissions (location, SMS, etc.).

Geo-Fence Setup:

The system loads predefined unsafe zone coordinates (from a database or JSON file).

Background service continuously monitors the user's current location.

Real-Time Monitoring:

If the user enters a restricted area → immediate alert is shown.

If the user remains inside for too long → SOS suggestion is triggered.

Emergency Activation:

User presses the SOS button or system auto-triggers it after certain thresholds (e.g., no motion + inside danger zone).

The system shares current coordinates + user info to emergency contacts.
Demo:-https://youtu.be/f-fvMzDwAnE?si=7eM_nu5NT-4GtJDC

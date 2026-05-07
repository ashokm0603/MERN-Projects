# Software Requirements Specification (SRS)
## Project 31: First Aid Guide & Emergency Locator (Health & Wellness)

### 1. Project Description
This application serves as a critical utility during medical emergencies. It provides immediate, offline-accessible illustrated steps for common first aid procedures (like CPR, choking, or burns) and utilizes the device's GPS to quickly locate and provide directions to the nearest hospitals, clinics, or 24/7 pharmacies.

### 2. Core Scope
The application must prioritize offline capabilities for the first aid guides, integration with Maps APIs for location services, and an incredibly fast, panic-proof user interface.

### 3. Functionalities (Minimum 25)

#### First Aid & Emergency Guides
1. **Offline First Aid Library:** A comprehensive database of first aid procedures stored locally on the device.
2. **Panic-Proof UI:** Large, high-contrast buttons for the most common emergencies (CPR, Bleeding, Choking) on the home screen.
3. **Step-by-Step Illustrations:** Clear, bold illustrations accompanying text instructions.
4. **Audio Instructions:** A text-to-speech button that reads the steps out loud so the user can keep their hands free.
5. **CPR Metronome:** A built-in audio metronome playing at 100-120 beats per minute to guide chest compressions.
6. **Search Functionality:** A prominent search bar to quickly find specific injuries or ailments.

#### Location Services
7. **Auto-GPS Detection:** Instantly pinpoint the user's current location upon opening the app.
8. **Nearest Hospital Locator:** Display a list or map view of the closest emergency rooms.
9. **Pharmacy Locator:** Filter map results to show only open 24/7 pharmacies.
10. **One-Tap Navigation:** Deep link directly into Google Maps or Apple Maps for immediate turn-by-turn directions to the selected facility.
11. **Share My Location:** A single button to send the exact GPS coordinates and a Google Maps link via SMS to a contact.

#### Emergency Communication
12. **Direct Emergency Call:** A massive red button to instantly dial the local emergency number (e.g., 911, 112).
13. **Dynamic Emergency Numbers:** Automatically change the emergency number based on the country the GPS detects the user is in.
14. **Emergency Contacts List:** Store up to 5 personal emergency contacts (ICE).
15. **SOS SMS Broadcast:** Send a pre-written SMS containing the user's location to all emergency contacts simultaneously.

#### Personal Medical Profile (Local Storage)
16. **Medical ID Dashboard:** A localized screen displaying the user's blood type, known allergies, and chronic conditions.
17. **Current Medications List:** A list of medications the user is currently taking, vital for paramedics.
18. **Organ Donor Status:** A toggle indicating if the user is a registered organ donor.
19. **Lock Screen Widget (Mobile web/PWA):** Instructions on how to add the medical ID to the phone's lock screen.

#### System & Admin Features
20. **Multi-Language Support:** First aid guides available in English, Spanish, French, etc., toggleable instantly.
21. **Content Update Syncing:** Fetch the latest medical guidelines (e.g., AHA CPR updates) when connected to WiFi.
22. **Accessibility Features:** High-contrast mode and dynamic text sizing for visually impaired users.
23. **Admin Dashboard:** For medical professionals to submit or update the first aid content for review.
24. **Analytics (Anonymized):** Track the most searched emergencies to improve the placement of guides on the home screen.
25. **No-Login Requirement:** Ensure the core features (Guides and Maps) are accessible immediately without forcing the user to create an account.

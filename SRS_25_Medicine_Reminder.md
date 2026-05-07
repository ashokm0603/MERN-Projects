# Software Requirements Specification (SRS)
## Project 25: Medicine Reminder & Refill Tracker (Health & Wellness)

### 1. Project Description
The Medicine Reminder & Refill Tracker is a comprehensive health management application designed to help users manage their daily medication schedules, track pill inventory, and receive timely alerts for both doses and prescription refills. It also features a pharmacy locator to assist users in finding the nearest open pharmacies.

### 2. Core Scope
The app revolves around complex scheduling algorithms, robust notification delivery systems (push/email/SMS), inventory management, and integration with mapping APIs.

### 3. Functionalities (Minimum 25)

#### Medication Management
1. **Add Medication:** Input medicine name, dosage, form (pill, liquid, injection), and instructions (e.g., "take with food").
2. **Medication Database Search:** Auto-complete suggestions for common drug names to prevent spelling errors.
3. **Pill Identification:** Upload a photo of the pill, and the AI suggests what medicine it might be based on color and shape (Optional/Advanced).
4. **Dosage Scheduling:** Set complex schedules (e.g., every 8 hours, 3 times a day, every other day).
5. **Inventory Tracking:** Input the total number of pills currently on hand.

#### Reminders & Alerts
6. **Push Notifications:** In-app and browser push notifications when a dose is due.
7. **Snooze Functionality:** Allow users to snooze a reminder for 15, 30, or 60 minutes.
8. **Mark as Taken/Skipped:** Log whether a dose was taken on time, delayed, or missed entirely.
9. **Low Stock Alert:** Automatically trigger a "Time to Refill" alert when the inventory drops below a user-defined threshold (e.g., 5 pills left).
10. **Refill Reminders:** Set a specific date to remind the user to call the doctor for a new prescription.

#### Tracking & Analytics
11. **Adherence Dashboard:** Visual charts showing the user's medication adherence rate (e.g., "You took 95% of your doses on time this week").
12. **Medication Logbook:** A calendar view showing the history of all taken and missed doses.
13. **Export Health Report:** Generate a PDF report of medication adherence to share with a doctor or caregiver.
14. **Side Effect Logger:** A quick journal feature to log any adverse reactions experienced after taking a specific medication.

#### Pharmacy & Healthcare Integration
15. **Pharmacy Locator:** Integration with Google Maps API to show nearby pharmacies on a map.
16. **Pharmacy Details:** Display pharmacy hours, phone numbers, and distance from the user.
17. **Doctor Contact Book:** Store contact information for the prescribing doctors.
18. **Prescription Upload:** Securely upload and store photos of paper prescriptions for reference.

#### Caregiver & Family Features
19. **Caregiver Access:** Allow a user to grant read-only access to a family member or nurse to monitor their adherence.
20. **Dependents Management:** A parent can manage medication schedules for multiple children from a single account.
21. **Missed Dose Alerts (Caregiver):** Send an SMS to the caregiver if the primary user misses a critical dose by more than 2 hours.

#### System Setup & Security
22. **User Registration:** Secure signup process ensuring HIPAA-compliant data handling practices.
23. **Data Encryption:** Encrypt all sensitive medical data at rest in the database.
24. **Biometric/PIN Lock:** Option to lock the app on mobile devices using FaceID or a custom PIN for privacy.
25. **Admin Dashboard:** Monitor system performance and notification delivery success rates without viewing encrypted user data.

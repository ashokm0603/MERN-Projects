# Software Requirements Specification (SRS)
## Project 12: Neighborhood Alert System (Social Impact)

### 1. Project Description
The Neighborhood Alert System is a hyperlocal community notification platform that keeps residents informed about events directly affecting their immediate area. Users can post and receive real-time alerts for power cuts, water supply disruptions, road closures, local events, safety warnings, and other neighborhood-level news via an intuitive pin-based map interface, ensuring that only users within the relevant geographic area are notified.

### 2. Core Scope
The application relies on geolocation, an interactive map interface, radius-based alert filtering, and a real-time push notification infrastructure. It ensures alerts are hyper-targeted to specific geographic zones to prevent information overload for users outside the affected area.

### 3. Functionalities (Minimum 25)

#### Alert Creation & Posting
1. **Geotagged Alert Posting:** Users place a pin on a map to mark the exact location of an incident or event before submitting an alert.
2. **Alert Category Selection:** Choose from predefined alert types: Power Outage, Water Supply, Road Block, Safety Warning, Community Event, Lost & Found, and General Info.
3. **Alert Radius Setting:** Posters define the radius of impact (e.g., 500m, 1km, 5km) to target only residents within the affected zone.
4. **Rich Alert Description:** Add a detailed text description, relevant photos, and an estimated duration or resolution time.
5. **Scheduled Alerts:** Schedule alerts for planned events (e.g., a water shutdown scheduled for next Tuesday) in advance.
6. **Anonymous Posting Option:** Allow users to post alerts without revealing their identity for sensitive safety warnings.

#### Map Interface & Discovery
7. **Interactive Map View:** A primary map view displaying all active alerts as categorized, color-coded pins in the user's area.
8. **Radius-Based Filtering:** Automatically display only alerts within the user's configured notification radius.
9. **Category Filter Layer:** Toggle map layers to show or hide specific alert categories (e.g., hide "Events," show only "Safety").
10. **Alert Detail Pop-Up:** Click a map pin to view full alert details, including description, timestamp, photos, and community comments.
11. **List View Mode:** An alternative list/feed view of active alerts sorted by recency or proximity.

#### Community Interaction & Verification
12. **Upvote / Confirm System:** Residents can confirm ("This is accurate") or dispute ("Can't verify this") an alert, building a community-sourced credibility score.
13. **Credibility Score Display:** Show how many users have confirmed an alert to help others gauge its reliability.
14. **Commenting on Alerts:** Allow users to add context, updates, or ask questions in a comment thread below each alert.
15. **Mark as Resolved:** Posters or a majority of confirming users can mark an alert as Resolved, visually archiving it on the map.

#### Notifications & Alerts Delivery
16. **Push Notifications:** Send real-time push notifications to all users whose location falls within the alert's defined radius.
17. **SMS Alerts for Critical Types:** For Safety or Emergency category alerts, send an SMS message to users with verified phone numbers.
18. **Email Digest:** Send a daily or weekly email digest summarizing all alerts in the user's area.
19. **Quiet Hours Setting:** Allow users to configure hours during which non-urgent notifications are suppressed.

#### User Account & Settings
20. **User Registration & Login:** Secure registration with email/password or Google OAuth.
21. **Home Location Setup:** Users set a primary "home" location, which is used as the default center for their alert map and notification radius.
22. **Multi-Location Watch:** Allow users to monitor multiple locations (e.g., home and workplace) simultaneously.
23. **Notification Preference Control:** Granular settings to choose which alert categories trigger push, SMS, and email notifications.

#### Admin & Moderation
24. **Admin Moderation Panel:** Review and remove false, inappropriate, or duplicate alerts flagged by the community.
25. **Alert Analytics Dashboard:** View heatmaps of alert frequency by area, most common alert types, and peak posting times.
26. **Official Channel Accounts:** Allow verified local authorities (municipality, police) to post high-credibility official alerts.

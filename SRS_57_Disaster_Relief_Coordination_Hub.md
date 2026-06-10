# Software Requirements Specification (SRS)
## Project 57: Disaster Relief Coordination Hub (Community & Civic)

### 1. Project Description
The Disaster Relief Coordination Hub is a crisis management web platform designed to facilitate rapid, organized response to natural disasters, public health emergencies, and large-scale civic crises. It provides a map-based dashboard where coordinators can visualize the geographic distribution of available resources (food, water, medical supplies, shelter) and unmet community needs, enabling intelligent dispatch decisions and preventing duplication of relief efforts.

### 2. Core Scope
The application focuses on resource and needs logging, map-based geographic visualization, volunteer coordination, status tracking, and real-time communication between relief teams and coordinators. It is designed to be operational during connectivity-constrained environments and must prioritize speed, clarity, and ease of use under stressful conditions.

### 3. Functionalities (Minimum 25)

#### Needs Reporting
1. **Community Needs Submission:** Citizens or field volunteers can submit a need report specifying location (map pin or address), type of need (Food, Water, Medical, Shelter, Evacuation, Other), urgency level (Critical, High, Medium), and a brief description.
2. **Anonymous Need Reporting:** Allow submissions without requiring account registration to lower barriers during emergencies.
3. **Photo Attachment:** Include photos with a need report to provide coordinators with visual context.
4. **Needs Categorization & Tagging:** Automatically categorize submitted needs and allow coordinators to add additional tags.
5. **Duplicate Detection:** Alert coordinators when a newly submitted need is geographically close to an already-open, similar need to prevent duplicate response.

#### Resource Registration
6. **Resource Logging by Volunteers/Organizations:** NGOs, government teams, and individual volunteers log available resources with type (Food Packets, Water Bottles, Medical Kits, Ambulances, Shelter Capacity), quantity, and current location.
7. **Resource Status Tracking:** Mark resources as Available, En Route, Deployed, or Depleted.
8. **Volunteer Registration:** Volunteers register with their name, contact info, skills (Medical, Driving, Construction, Counseling), availability, and current location.
9. **Vehicle & Transport Fleet Logging:** Log available transport vehicles with capacity and current location for coordinating large-scale distribution.

#### Map-Based Dashboard (Coordinator View)
10. **Interactive Crisis Map:** A real-time map showing all active need pins and resource pins, color-coded and categorized with distinct icons.
11. **Heatmap Overlay:** Toggle a heatmap layer showing the density and severity of unmet needs by geographic area to prioritize zones.
12. **Resource Gap Visualization:** Automatically highlight geographic areas where reported needs significantly outpace logged resources.
13. **Filter & Layer Controls:** Toggle visibility of different need types, resource types, urgency levels, and volunteer locations on the map.
14. **Cluster View for Dense Zones:** Aggregate nearby pins into numbered clusters at lower zoom levels to prevent map clutter.

#### Assignment & Dispatch
15. **Need-to-Resource Assignment:** Coordinators assign specific resources or volunteers to an open need directly from the map interface.
16. **Volunteer Task Dispatch:** Send an in-app or SMS notification to a volunteer with their assigned task, location, and contact for the person in need.
17. **Response Status Tracking:** Track the status of each assigned need: Reported → Assigned → En Route → Resolved.
18. **Estimated Arrival Time Entry:** Responding volunteers can log their estimated arrival time, visible to both coordinators and the reporting party.

#### Communication
19. **Coordinator Broadcast Announcements:** Post urgent announcements visible to all logged-in volunteers (e.g., "Avoid Zone B — Road Blocked").
20. **Team Chat Channels:** Create specific communication channels per geographic zone or response team for focused coordination.
21. **SMS Integration for Field Volunteers:** Send critical updates via SMS for volunteers with limited smartphone/internet access.

#### Reporting & Analytics
22. **Real-Time Dashboard Statistics:** Live counts of open needs, resolved needs, active volunteers, and available resources.
23. **Response Time Analytics:** Track average time from need submission to assignment and to resolution.
24. **Post-Crisis Incident Report:** Generate a comprehensive report of all needs logged, resources deployed, and response timelines for organizational debriefing.

#### Admin & Access Control
25. **Role-Based Access Control:** Distinct roles for Citizens (report only), Volunteers (log and update), Coordinators (assign and manage), and Admins (full access).
26. **Organization Management:** Allow verified NGOs and government bodies to register as organizations, manage their own volunteer teams, and resource pools.

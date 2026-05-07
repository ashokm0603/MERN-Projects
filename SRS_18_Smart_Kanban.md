# Software Requirements Specification (SRS)
## Project 18: Smart Kanban with AI Prioritization (Productivity)

### 1. Project Description
Smart Kanban is a next-generation project management tool that goes beyond a standard drag-and-drop board. It utilizes an AI engine to analyze task descriptions, deadlines, and current workloads to automatically suggest priority levels and assign labels, ensuring teams always work on the most impactful tasks first.

### 2. Core Scope
The application requires a highly interactive UI (drag-and-drop), real-time database updates for collaboration, and integration with an LLM for task analysis and automated tagging.

### 3. Functionalities (Minimum 25)

#### Board & Task Management
1. **Interactive Kanban Board:** Drag-and-drop columns (To Do, In Progress, Review, Done).
2. **Custom Columns:** Allow users to add, rename, or delete columns to fit their workflow.
3. **Task Creation:** Modal to input task title, description, due date, and assignees.
4. **Rich Text Editing:** Support Markdown and rich text formatting within task descriptions.
5. **Subtasks:** Break down complex tasks into smaller, checkable subtasks.
6. **File Attachments:** Upload images and documents directly to a task card.

#### AI Prioritization Engine
7. **Auto-Priority Tagging:** AI analyzes the task description and assigns a priority (Low, Medium, High, Critical).
8. **Effort Estimation:** AI estimates the time required to complete a task based on historical data and description.
9. **Duplicate Detection:** AI flags new tasks that sound suspiciously similar to existing open tasks.
10. **Dependency Suggestions:** AI suggests if a task might be blocked by or related to another task.
11. **Daily "Focus" Suggestions:** AI recommends the top 3 tasks a user should focus on today based on deadlines and priority.

#### Collaboration & Notifications
12. **Real-Time Syncing:** Board updates instantly for all connected users via WebSockets.
13. **Task Assignment:** Assign specific team members to tasks.
14. **Comments Section:** A thread within each task card for team discussion.
15. **@Mentions:** Notify specific users by mentioning them in comments.
16. **Activity Log:** An audit trail showing who moved a card, changed a deadline, or left a comment.
17. **Email/Push Notifications:** Alerts for approaching deadlines or when assigned a new task.

#### Analytics & Search
18. **Global Search:** Search bar to find tasks across all boards using keywords or tags.
19. **Filtering Options:** Filter the board by assignee, priority, or due date.
20. **Burndown Charts:** Visual representation of work completed versus time remaining in a sprint.
21. **Cumulative Flow Diagram:** Track bottlenecks by showing how many tasks are in each column over time.

#### Account & Admin Setup
22. **Workspace Creation:** Create isolated workspaces for different departments or projects.
23. **Role Management:** Admin, Editor, and Viewer permission levels.
24. **Third-Party Integrations:** Webhooks for Slack or GitHub to create tasks automatically from external triggers.
25. **Data Export:** Export the entire Kanban board as a CSV or JSON file.

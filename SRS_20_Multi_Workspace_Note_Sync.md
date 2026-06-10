# Software Requirements Specification (SRS)
## Project 20: Multi-Workspace Note Sync (Productivity)

### 1. Project Description
Multi-Workspace Note Sync is a powerful, developer-friendly note-taking application that supports Markdown formatting, hierarchical organization, cross-note linking (like a personal wiki), and seamless real-time synchronization across all of a user's devices. It is designed for knowledge workers, developers, researchers, and students who need a powerful yet distraction-free environment to capture, organize, and connect their ideas and knowledge.

### 2. Core Scope
The application focuses on Markdown-based writing, rich organizational features (tags, folders, cross-links), real-time multi-device synchronization, and powerful search capabilities. It must be highly performant with offline support and conflict resolution for edits made on multiple devices.

### 3. Functionalities (Minimum 25)

#### Note Creation & Editing
1. **Markdown Editor:** A dual-pane editor with live Markdown preview, supporting all standard Markdown syntax (headings, lists, code blocks, tables, images, etc.).
2. **WYSIWYG Toggle:** Switch between a raw Markdown editing mode and a rich-text WYSIWYG editing mode seamlessly.
3. **Code Block Syntax Highlighting:** Automatically apply syntax highlighting for code blocks in over 50 programming languages.
4. **Embed Support:** Embed images, links, YouTube videos, and other media directly within notes.
5. **Slash Command Menu:** Type "/" to trigger an inline menu for quickly inserting headings, lists, code blocks, dividers, and other formatting elements.

#### Organization & Structure
6. **Workspaces:** Create multiple separate workspaces (e.g., "Personal," "Work," "Research") to keep content domains isolated.
7. **Nested Folder Hierarchy:** Organize notes within customizable, infinitely nested folder structures.
8. **Tagging System:** Assign one or more tags to any note for cross-folder categorization and quick filtering.
9. **Tag View:** A dedicated view that filters and shows all notes associated with a selected tag.
10. **Starred/Pinned Notes:** Star important notes to pin them to a quick-access section at the top of the sidebar.

#### Cross-Linking & Knowledge Graph
11. **[[Wiki-Style Note Linking]]:** Create internal links between notes using double-bracket syntax; links are auto-completed as you type a note title.
12. **Backlinks Panel:** Every note displays a "Backlinks" panel showing all other notes that link to the current one.
13. **Knowledge Graph View:** An interactive visual graph showing all notes and the link connections between them, allowing users to explore their knowledge network.

#### Synchronization & Multi-Device
14. **Real-Time Cloud Sync:** All changes are instantly synced to the cloud and reflected across all signed-in devices.
15. **Offline Mode:** Full read and write functionality when offline; changes are queued and synced automatically upon reconnection.
16. **Conflict Resolution:** Intelligent detection of simultaneous edits from multiple devices, with a clear merge/conflict resolution UI.
17. **Sync Status Indicator:** A visible indicator showing sync status (Synced, Syncing, Offline) at all times.

#### Search & Discovery
18. **Full-Text Search:** Fast, indexed full-text search across all notes, including content inside code blocks.
19. **Advanced Search Filters:** Narrow search results by workspace, folder, tag, creation date, or modification date.
20. **Recent Notes Panel:** Quick access sidebar showing recently created or modified notes.

#### Sharing & Collaboration
21. **Public Note Publishing:** Publish any note as a read-only public web page with a shareable link.
22. **Workspace Sharing:** Invite collaborators to a shared workspace with view-only or edit permissions.
23. **Export Options:** Export individual notes or entire notebooks as Markdown files, PDF, or HTML.

#### User Account & Settings
24. **User Authentication:** Secure login with email/password and Google OAuth.
25. **Version History:** Automatically save snapshots of every note, allowing users to view and restore any previous version.
26. **Custom Themes & Fonts:** Personalize the editor with light/dark themes, font families, and font size settings for comfortable long-form writing.

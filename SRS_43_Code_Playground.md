# Software Requirements Specification (SRS)
## Project 43: Code Playground & Share Tool (Education)

### 1. Project Description
The Code Playground is a web-based, interactive Integrated Development Environment (IDE) tailored for frontend web development. Similar to CodePen, it provides live HTML, CSS, and JavaScript editors that render output instantly. It is designed for students, teachers, and developers to easily prototype, share code snippets, and fork others' work.

### 2. Core Scope
The application requires embedding a code editor library (like Monaco Editor or CodeMirror), real-time DOM rendering inside an iframe, secure code storage, and a robust versioning/forking system.

### 3. Functionalities (Minimum 25)

#### Core Code Editor
1. **Three-Pane Layout:** Dedicated, resizable editor windows for HTML, CSS, and JS.
2. **Live Preview Window:** An iframe that instantly re-renders the result as the user types (with a slight debounce to prevent lag).
3. **Syntax Highlighting:** Color-coded syntax specifically tailored for HTML/CSS/JS using Monaco Editor.
4. **Auto-Complete & Emmet:** Built-in suggestions for tags, CSS properties, and Emmet abbreviation expansion for rapid HTML writing.
5. **Error Highlighting:** Real-time linting to underline syntax errors in red directly in the code editor.

#### Project Configuration
6. **External Libraries (CDN):** A modal to quickly inject popular libraries (React, Vue, Bootstrap, Tailwind, jQuery) via CDN links.
7. **CSS Preprocessors:** Support for compiling SCSS or LESS into standard CSS before rendering.
8. **Console Output:** A simulated browser console within the UI to view `console.log()` outputs without opening Chrome DevTools.
9. **Auto-Save:** Continuously save the user's progress to `localStorage` to prevent data loss on accidental refresh.
10. **Save to Cloud (Pen):** Save the current state of the workspace as a unique project (a 'Pen') linked to the user's account.

#### Sharing & Collaboration
11. **Unique URL Generation:** Every saved project gets a unique, shareable URL.
12. **Forking System:** A "Fork" button allowing users to duplicate someone else's public project into their own account to modify it without altering the original.
13. **Embed Codes:** Generate an HTML `<iframe>` snippet so users can embed their code playground directly into their personal blogs or portfolios.
14. **Export to ZIP:** Download the HTML, CSS, and JS files as a local `.zip` archive.
15. **Collaborative Mode (Advanced):** (Optional) Real-time cursor syncing allowing two users to type in the same file simultaneously.

#### Community & Browsing
16. **Explore Feed:** A homepage showcasing "Trending" and "Staff Picked" public projects.
17. **Like/Heart System:** Allow users to upvote impressive projects.
18. **Commenting System:** A discussion thread below public projects to ask questions or suggest optimizations.
19. **Tags & Search:** Add tags (e.g., "Animation", "CSS Grid") to projects and a global search bar to find specific examples.
20. **User Profiles:** A public portfolio page showing a grid of all the projects a specific user has created.

#### Settings & Customization
21. **Editor Themes:** Allow users to switch the code editor theme (e.g., Dracula, Monokai, VS Code Dark).
22. **Font Size & Ligatures:** Settings to adjust font size, family, and enable coding ligatures (like Fira Code).
23. **View Toggles:** Buttons to quickly change the layout (e.g., Code on Left, Code on Top, Fullscreen Result).
24. **Private Projects:** A premium toggle to mark a project as "Private" so it doesn't appear in the explore feed or search results.
25. **Admin Panel:** Tools to moderate spam comments, ban malicious users, and feature specific projects on the homepage.

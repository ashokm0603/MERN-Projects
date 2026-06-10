# Software Requirements Specification (SRS)
## Project 48: Lab Report Builder (Education)

### 1. Project Description
The Lab Report Builder is a structured academic writing tool designed to help students, researchers, and educators create well-formatted, professional scientific lab reports efficiently. The platform provides template-driven report structures for common experiment types, guided section-by-section completion prompts, automatic table and graph generation from data input, citation management, and one-click export — eliminating the formatting burden and helping students focus on the scientific content of their work.

### 2. Core Scope
The application focuses on structured document authoring through predefined templates, guided content prompts per section, data visualization (tables/charts), scientific citation management, and multi-format export. It supports multiple scientific disciplines and experiment types commonly encountered in high school, undergraduate, and postgraduate settings.

### 3. Functionalities (Minimum 25)

#### Report Initialization
1. **Template Selection:** Choose from a library of templates covering common experiment types (Biology Dissection, Chemistry Titration, Physics Projectile, Control Group Experiment, Engineering Prototype Test, etc.).
2. **Custom Template Creation:** Advanced users or educators can define and save custom report templates for specific recurring experiment structures.
3. **Report Metadata Entry:** Input report details including title, student name, institution, course, supervisor, and submission date — automatically placed in the report header.
4. **Discipline-Specific Formatting:** Apply discipline-appropriate formatting conventions (APA, Vancouver for sciences; IEEE for engineering; MLA for environmental science).

#### Section-by-Section Guided Writing
5. **Guided Section Prompts:** Each report section (Aim, Hypothesis, Apparatus, Method, Results, Discussion, Conclusion) displays contextual guiding questions to help students write comprehensively.
6. **Rich Text Editor per Section:** Full rich-text editing (bold, italics, bullet points, subscript, superscript for chemical formulas) within each section.
7. **Hypothesis Builder:** A structured form guiding students to write a proper "If–Then–Because" hypothesis statement.
8. **Materials & Apparatus List:** A dedicated input tool for building an itemized apparatus list with quantity and specification fields.
9. **Step-by-Step Method Writer:** A numbered-step editor with drag-and-drop reordering for writing the experimental procedure.

#### Data Entry & Visualization
10. **Data Table Builder:** An interactive, spreadsheet-like table editor for entering raw experimental data with customizable rows, columns, and headers.
11. **Automatic Chart Generation:** Generate appropriate charts (line graphs, bar charts, scatter plots) directly from the data entered in the data table.
12. **Chart Customization:** Edit chart titles, axis labels, units, gridlines, and colors for inclusion in the report.
13. **Statistical Calculation Tools:** Automatically calculate mean, median, standard deviation, percentage error, and uncertainty directly from entered data.
14. **Uncertainty & Error Analysis Section:** A dedicated, guided section for identifying sources of error and calculating experimental uncertainty.

#### Citations & References
15. **In-Text Citation Inserter:** Insert numbered or author-date in-text citations directly within the report body.
16. **Reference Manager:** Add and manage reference entries (books, journal articles, websites) using structured input forms.
17. **Auto-Formatted Reference List:** Automatically generate a properly formatted References/Bibliography section at the end of the report based on added citations and the selected citation style.
18. **DOI / URL Auto-Fetch:** Paste a DOI or URL to automatically populate all citation fields using metadata from the source.

#### Review & Collaboration
19. **Supervisor Comment Mode:** Instructors can view submitted reports and leave inline comments on specific sections for feedback.
20. **Revision History:** Track all saved edits with timestamps for academic integrity and version management.
21. **Plagiarism Check Integration:** Optional integration with a plagiarism detection API (Turnitin, Copyleaks) to verify originality before submission.

#### Export & Submission
22. **PDF Export:** Export the completed lab report as a cleanly formatted, print-ready PDF document.
23. **DOCX Export:** Export the report as an editable Microsoft Word document for further manual editing.
24. **Auto-Numbered Figures & Tables:** All figures and data tables are automatically numbered and captioned according to the report structure.

#### User Account & Management
25. **User Authentication:** Secure registration and login with student email or Google OAuth.
26. **Report Library Dashboard:** A personal dashboard showing all created reports with status (Draft, In Progress, Submitted) and quick access to continue editing.
27. **Report Sharing:** Share a read-only link to the report with supervisors or lab partners for review.

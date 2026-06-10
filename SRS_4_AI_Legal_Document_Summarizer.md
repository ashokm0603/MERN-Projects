# Software Requirements Specification (SRS)
## Project 4: AI-Powered Legal Document Summarizer (AI-Powered)

### 1. Project Description
The AI-Powered Legal Document Summarizer is a web platform designed to bridge the gap between complex legal language and everyday users. Users can upload contracts, NDAs, terms of service agreements, or other legal documents, and the AI returns plain-language summaries, identifies potentially risky clauses, highlights obligations, and flags unusual or unfavorable conditions — empowering individuals and small businesses to understand legal documents without requiring a lawyer.

### 2. Core Scope
The application focuses on document ingestion, AI-based natural language processing for legal text, risk flagging, obligation extraction, and plain-language translation. It is designed for non-legal professionals who need to quickly understand the key implications of a legal document.

### 3. Functionalities (Minimum 25)

#### Document Upload & Ingestion
1. **Multi-Format Upload:** Support PDF, DOCX, and TXT document uploads with size and format validation.
2. **Drag-and-Drop Interface:** Provide an intuitive drag-and-drop upload zone for easy document submission.
3. **Document Type Selection:** Allow users to specify the document type (Contract, NDA, Terms of Service, Lease, etc.) to improve AI context.
4. **Multi-Document Queue:** Allow users to upload and process multiple documents in a single session.
5. **Paste Text Mode:** Provide an alternative plain-text input field for users to paste document content directly.

#### AI Analysis & Summarization
6. **Executive Summary:** Generate a concise, plain-language executive summary (3–5 sentences) of the entire document.
7. **Section-by-Section Breakdown:** Summarize each identifiable section or clause of the document in simple language.
8. **Key Obligation Extraction:** Automatically identify and list all obligations, deadlines, and responsibilities imposed on each party.
9. **Red Flag Detection:** Highlight clauses that are potentially unfavorable, one-sided, unusual, or commonly contested.
10. **Risk Severity Scoring:** Assign a risk level (Low / Medium / High) to each identified flag with an explanation.

#### Clause & Term Analysis
11. **Defined Terms Glossary:** Extract all capitalized defined terms from the document and provide plain-language definitions.
12. **Penalty & Liability Clause Identification:** Specifically flag clauses related to financial penalties, indemnification, and limitation of liability.
13. **Termination Conditions Summary:** Clearly list all conditions under which the agreement can be terminated by either party.
14. **Renewal & Auto-Renewal Alerts:** Identify clauses regarding automatic contract renewal and relevant notice periods.
15. **Governing Law & Jurisdiction:** Extract and highlight the applicable law and dispute resolution jurisdiction.

#### Comparison & Review Tools
16. **Side-by-Side View:** Display original legal text alongside the plain-language translation for each section.
17. **Clause Search:** Allow users to search for specific topics (e.g., "payment," "confidentiality") to jump to relevant sections.
18. **Document Version Comparison:** Compare two versions of the same document to identify additions, removals, and changed clauses.

#### Reporting & Export
19. **Summary Report Export:** Download the full AI analysis as a formatted PDF or DOCX report.
20. **Highlighted Document Download:** Export the original document with risk-flagged clauses visually highlighted.
21. **Shareable Analysis Link:** Generate a secure link to share the document analysis with a colleague or advisor.

#### User Account & Management
22. **User Authentication:** Secure registration and login with email/password and Google OAuth.
23. **Document Library:** Store and manage all previously analyzed documents in a personal dashboard.
24. **Analysis History:** View past analyses, re-read summaries, and re-download reports without re-processing.

#### Notifications & Compliance
25. **Email Summary Delivery:** Send the document summary and risk flags directly to the user's email after analysis.
26. **Deadline Reminders:** Allow users to set reminders for important dates or deadlines extracted from the document.
27. **Privacy & Confidentiality Assurance:** Display a clear data handling policy, with all uploaded documents processed securely and not stored beyond user-defined retention periods.

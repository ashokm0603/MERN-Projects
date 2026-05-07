# Software Requirements Specification (SRS)
## Project 8: Fake News Detector (AI-Powered)

### 1. Project Description
The Fake News Detector is an AI-driven web application designed to combat misinformation. Users can submit news article URLs or paste text directly. The system uses natural language processing (NLP) to cross-reference facts, analyze sentiment, and check credibility against trusted news sources, ultimately providing a "Trust Score" for the submitted content.

### 2. Core Scope
The platform provides a consumer-facing verification tool, an API for developers, and an admin dashboard for tuning the machine learning models. It emphasizes transparency by showing the sources used to verify or debunk claims.

### 3. Functionalities (Minimum 25)

#### User Interface & Input Methods
1. **URL Submission:** Users can paste a link to an article for automated scraping and analysis.
2. **Text Input:** A text area for pasting raw text, social media posts, or WhatsApp forwards.
3. **Image Upload (OCR):** Upload screenshots of news or tweets, utilizing OCR to extract and analyze the text.
4. **Browser Extension Integration:** (Optional scope) Endpoints to support a future Chrome extension.

#### AI & Analysis Engine
5. **Content Scraping:** Extract the main text, headline, and author from the submitted URL, ignoring ads and navbars.
6. **Fact-Checking API Integration:** Cross-reference claims with established fact-checking APIs (e.g., Google Fact Check Tools).
7. **Credibility Scoring:** Generate a final Trust Score (0-100%) based on source reputation and text analysis.
8. **Clickbait Detection:** Analyze the headline versus the body content to flag sensationalized or misleading titles.
9. **Sentiment & Bias Analysis:** Detect extreme political bias or emotionally manipulative language.
10. **Source Verification:** Check the domain against a database of known satirical, biased, or fake news sites.

#### Results Presentation
11. **Detailed Report Dashboard:** Display the Trust Score prominently with color coding (Green/Yellow/Red).
12. **Highlighting Suspicious Claims:** Highlight specific sentences in the text that are likely false or unverified.
13. **Related Verified Articles:** Provide links to the same story covered by highly reputable news outlets (e.g., Reuters, AP).
14. **Shareable Verification Card:** Generate an image summary of the result that users can easily share on social media.
15. **User Feedback (Crowdsourcing):** Allow users to vote on whether they agree with the AI's assessment (flagging false positives).

#### User Accounts (Optional for tracking)
16. **User Registration/Login:** Allow users to create accounts to track their verification history.
17. **Search History:** A dashboard showing previously verified links and their scores.
18. **Saved Articles:** Bookmark articles that have been verified for future reference.

#### Admin & System Features
19. **Admin Dashboard:** Monitor system usage, API limits, and overall server health.
20. **Domain Whitelist/Blacklist Management:** Admins can manually add or update the reputation scores of specific domains.
21. **Model Retraining Trigger:** Option for admins to trigger a model update based on newly flagged content.
22. **API Key Management:** Allow developers to generate API keys to integrate the detector into their own apps.
23. **Rate Limiting:** Protect the scraping and AI endpoints from abuse.
24. **Multi-Language Support:** Ability to detect and process news in multiple languages (e.g., English, Spanish, Hindi).
25. **Responsive Design:** Mobile-first layout ensuring the tool is usable on smartphones where most fake news spreads.

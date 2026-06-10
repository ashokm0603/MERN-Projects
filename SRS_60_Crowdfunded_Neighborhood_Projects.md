# Software Requirements Specification (SRS)
## Project 60: Crowdfunded Neighborhood Projects (Community & Civic)

### 1. Project Description
The Crowdfunded Neighborhood Projects platform is a civic tech solution that empowers residents to propose, vote on, and collectively fund improvements and initiatives for their local community. Whether it's installing a new playground, renovating a community center, planting a neighborhood garden, or installing better street lighting, this platform gives residents democratic control over how community improvement funds are raised and spent — bridging the gap between government inaction and community need.

### 2. Core Scope
The application focuses on project proposal submission, community democratic voting, crowdfunding fund collection, transparent financial management, project progress updates, and impact documentation. It requires strong geographic verification to ensure only genuine local residents can vote on and fund projects within their area.

### 3. Functionalities (Minimum 25)

#### Project Proposal
1. **Project Proposal Submission:** Any verified resident can submit a project proposal with a title, detailed description, photos, location (map pin), project category (Infrastructure, Green Spaces, Community Services, Safety, Culture & Arts, Youth & Sports), and a funding goal.
2. **Budget Breakdown:** Proposers provide an itemized budget breakdown showing how the requested funds will be allocated.
3. **Supporting Documents:** Attach supporting documents (cost estimates, vendor quotes, photos of current state) to strengthen the proposal.
4. **Proposal Revision:** Proposers can edit their proposal based on community feedback during the voting phase before it is approved.
5. **Project Categorization & Tags:** Assign relevant tags to improve discoverability (e.g., "Playground," "Lighting," "Park," "Safety").

#### Community Verification & Eligibility
6. **Resident Verification:** New users verify their neighborhood residency via address entry and an OTP sent to a utility bill-registered mobile number or email.
7. **Geographic Voting Zones:** Define voting and funding eligibility zones (neighborhood or ward boundaries); users can only vote on and fund projects within their verified zone.
8. **One Vote Per Verified Resident:** Strict enforcement ensuring each verified resident can cast only one vote on any given project.

#### Democratic Voting
9. **Community Voting Phase:** Newly submitted proposals enter a voting phase; residents vote "Support" or "Not Now" to gauge community interest.
10. **Voting Dashboard:** Display real-time vote counts, support percentage, and time remaining in the voting phase for each project.
11. **Vote Threshold for Funding Phase:** Projects that receive a configurable minimum support threshold (e.g., 60% support, minimum 50 votes) advance to the crowdfunding phase.
12. **Failed Proposal Archive:** Projects that don't reach the voting threshold are archived but remain viewable, with an option to resubmit after improvements.
13. **Endorsements by Local Leaders:** Allow verified local community leaders or elected representatives to add a public endorsement to proposals.

#### Crowdfunding
14. **Donation / Contribution System:** Eligible residents contribute any amount toward a project's funding goal using secure payment gateways (Razorpay, Stripe, UPI).
15. **Funding Progress Bar:** A prominent, live progress bar showing total funds raised vs. the project goal.
16. **Countdown to Funding Deadline:** A visible countdown timer for the crowdfunding window (e.g., 30 or 60 days).
17. **Backer Recognition:** List all contributors publicly (with optional anonymity) with their contribution amount, fostering community pride.
18. **Auto-Refund on Failed Funding:** If a project does not reach its funding goal by the deadline, all contributions are automatically and fully refunded.
19. **Overfunding Handling:** Define a policy for excess funds (e.g., held for project Phase 2 or donated to community reserve) displayed transparently to backers.

#### Project Execution & Transparency
20. **Fund Release in Milestones:** Proposers request fund disbursements in milestone tranches; admins verify completion before releasing the next tranche.
21. **Project Update Posts:** Proposers post regular progress updates with photos, completed milestones, and upcoming steps, visible to all community members.
22. **Backer-Only Q&A:** Backers can ask the project team questions; responses are public to all project followers.
23. **Completion Report:** Upon project completion, proposers submit a final report with photos, final expenditure breakdown, and impact statement.

#### Admin & Governance
24. **Admin Review & Approval:** Platform admins review submitted proposals for feasibility, community standards compliance, and legal permissibility before they enter the voting phase.
25. **Financial Transparency Dashboard:** A public-facing dashboard showing total funds raised across all projects, active projects, completed projects, and aggregate community impact.
26. **Audit Trail:** All financial transactions, fund releases, and administrative decisions are logged with timestamps for full accountability and public access.

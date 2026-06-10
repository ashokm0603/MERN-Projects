# Software Requirements Specification (SRS)
## Project 28: Fitness Challenge Social App (Health & Wellness)

### 1. Project Description
The Fitness Challenge Social App is a community-driven fitness motivation platform where users create or join time-bound fitness challenges (e.g., "30-Day Plank Challenge," "10K Steps Every Day for a Month"), invite friends, log daily workouts, and compete on leaderboards. The social accountability and friendly competition features are designed to make exercise more engaging, consistent, and fun, helping users build lasting fitness habits.

### 2. Core Scope
The application focuses on challenge creation, participant management, daily workout logging, leaderboard-driven competition, social interaction, and progress visualization. It must handle real-time leaderboard updates and support a variety of fitness challenge types and activity categories.

### 3. Functionalities (Minimum 25)

#### Challenge Creation & Discovery
1. **Challenge Creator:** Create a named fitness challenge with a description, start date, end date, fitness category (Running, Strength, Flexibility, Steps, Cycling, etc.), and a specific daily or weekly goal metric.
2. **Challenge Types:** Support multiple goal structures — Daily Target (e.g., 10,000 steps/day), Total Accumulation (e.g., run 50km over 30 days), and Consistency Streak (e.g., complete a workout for 20 out of 30 days).
3. **Public vs. Private Challenges:** Create challenges that are open to any platform user (Public) or invite-only (Private) for groups of friends.
4. **Challenge Discovery Feed:** Browse and join active public challenges categorized by fitness type, difficulty level, and popularity.
5. **Featured Challenges:** Platform-curated weekly featured challenges highlighting popular or timely fitness goals.

#### Invitation & Participant Management
6. **Invite Friends:** Send challenge invitations to friends via in-app notification, email, or a shareable invite link.
7. **Join Request Approval:** For private challenges, the creator can approve or decline join requests.
8. **Participant Roster:** View a list of all participants in a challenge with their current progress and ranking.
9. **Team Mode:** Form teams within a challenge where team members' progress is pooled together for team leaderboard rankings.

#### Workout Logging
10. **Daily Activity Log:** Log daily workout completion for the active challenge with relevant metrics (distance, duration, reps, sets, steps).
11. **Quick Log Button:** A prominent "Log Today's Workout" button on the challenge dashboard for one-tap logging.
12. **Manual Entry & Device Sync:** Enter metrics manually, with optional integration with fitness APIs (Google Fit, Apple Health) for automatic data pull.
13. **Proof Photo Upload:** Optionally upload a photo as proof of workout completion (e.g., a screenshot of the fitness app).
14. **Rest Day Logging:** Mark intentional rest days to distinguish from missed days in the streak calculation.

#### Leaderboards & Competition
15. **Real-Time Leaderboard:** A live leaderboard ranking all participants by their cumulative challenge metric, updated as new logs are submitted.
16. **Personal Best Tracking:** Track and display the user's personal best performance across all past challenges of the same type.
17. **Weekly Sub-Leaderboard:** A fresh weekly ranking within the challenge to keep motivation high even if someone falls behind overall.

#### Social & Community
18. **Activity Feed:** A social feed within each challenge showing recent workout logs, milestone achievements, and motivational posts from participants.
19. **Cheers & Encouragement:** Cheer on fellow participants with emoji reactions or short motivational messages on their log entries.
20. **Challenge Wall:** A shared discussion board within the challenge for tips, questions, and community interaction.
21. **Challenge Sharing:** Share a challenge's leaderboard or personal progress card to external social media.

#### Progress & Achievements
22. **Personal Progress Dashboard:** Visual charts showing daily/weekly progress toward the challenge goal.
23. **Milestone Badges:** Earn badges for reaching percentage milestones (25%, 50%, 75%, 100% of a challenge goal).
24. **Challenge Completion Certificate:** Receive a downloadable digital certificate upon successfully completing a challenge.
25. **Overall Fitness Statistics:** A personal profile page showing all-time stats: challenges joined, completed, total workouts logged, and badges earned.

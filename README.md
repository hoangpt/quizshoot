# Quizshoot - Kahoot Clone

Below are the features list of **QuizShoot**. Please to go for more detail on requirement and technical design
- [System Design](docs/High_level_design.md) 
- [Optimization](docs/Consideration.md)
- [US4: user paticipants requirements](docs/US4-Quiz_participant/Requirements.md)
- [US4: user paticipants flows](docs/US4-Quiz_participant/Flows.md)

### 1. **User Authentication and Profiles**

-   **User Registration/Login**: Enable users to sign up or log in using email, social media, or third-party authentication services.
-   **Profile Management**: Users should be able to manage their profiles (name, avatar, etc.).
-   **Role-based Access**: Different roles such as teachers (quiz creators) and students (quiz participants).

### 2. **Quiz Creation**

-   **Question Types**: Support for multiple question types like multiple-choice, true/false, polls, or short answers.
-   **Media Integration**: Allow embedding of images, videos, and audio clips in the questions.
-   **Timed Questions**: Set time limits for answering each question.
-   **Point Scoring**: Ability to allocate different points based on correct answers and speed.
-   **Question Bank**: Ability for users to save questions in a bank for reuse in future quizzes.
-   **Randomized Question Order**: Randomize the order of questions and answer options to avoid cheating.

### 3. **Quiz Hosting**

-   **Real-Time Gameplay**: Quizzes are hosted live, with all participants joining simultaneously.
-   **Unique Game Pin**: Generate a unique PIN or code for players to join the session.
-   **Lobby**: A waiting area for participants to join before the game starts.
-   **Live Leaderboard**: A real-time leaderboard showing players' rankings based on performance.
-   **Game Modes**: Different modes like team play or individual play.

### 4. **Quiz Participation**

-   **Device Compatibility**: Players can join quizzes using smartphones, tablets, or computers.
-   **Join via Code**: Players enter a session code to join the quiz.
-   **Live Feedback**: Immediate feedback on whether an answer is correct or incorrect.
-   **Answer Streaks**: Reward for consecutive correct answers.
-   **Rank Display**: Players can see their rank compared to others during the quiz.

### 5. **Score Calculation and Leaderboards**

-   **Time-Based Scoring**: Score based on how quickly players answer questions correctly.
-   **Leaderboard Display**: Show top performers after each round or at the end of the quiz.
-   **Final Score**: Show the total score and ranking at the end of the quiz.

### 6. **Reporting and Analytics**

-   **Performance Overview**: Detailed reports on how each participant performed.
-   **Quiz Statistics**: Analytics on question difficulty, participant engagement, and quiz performance.
-   **Downloadable Reports**: Allow quiz creators to export the results (e.g., CSV, PDF).

### 7. **Customization and Settings**

-   **Custom Themes**: Allow quiz creators to customize themes, colors, and background music.
-   **Quiz Privacy Settings**: Choose between public and private quizzes.
-   **Question Timer Customization**: Customize the time limit for each question.
-   **Flexible Question Order**: Option to shuffle questions and answers for each quiz session.

### 8. **Social and Sharing Features**

-   **Shareable Quiz Links**: Allow users to share quiz links or results on social media.
-   **Quiz Duplication**: Allow users to duplicate existing quizzes and make modifications.
-   **Comments and Reviews**: Enable feedback on quizzes from participants.

### 9. **Multiplayer and Interaction**

-   **Team Mode**: Support for team-based play with a shared score.
-   **Chat and Reactions**: Allow participants to chat or react during the quiz.
-   **Player Avatars**: Customizable avatars or icons for each participant.

### 10. **Gamification**

-   **Badges and Achievements**: Reward players with badges or achievements for consistent participation or high scores.
-   **Level System**: Introduce levels that users can progress through as they play more quizzes.
-   **Daily Challenges**: Offer challenges or quizzes with special rewards for participation.

### 11. **Administrative Tools**

-   **Quiz Moderation**: Allow hosts to kick or mute disruptive participants.
-   **Session Management**: Ability to pause, resume, or end the quiz at any time.
-   **Question Management**: Edit or skip questions during a live quiz session.

### 12. **Monetization (optional)**

-   **Premium Features**: Offer advanced features for a fee, such as additional customization options, larger player capacity, or more in-depth reporting.
-   **Ad Integration**: If free, you can integrate non-intrusive ads to monetize the platform.

### 13. **Responsive Design**

-   **Mobile-Friendly Interface**: Ensure the platform works smoothly across different screen sizes and devices.

### 14. **Localization and Language Support**

-   **Multi-language Support**: Allow quizzes and the platform to be translated into multiple languages.

### 15. **Backend and Scalability**

-   **Real-Time Backend**: Use a scalable backend like WebSockets for real-time data updates and smooth interaction during live quizzes.
-   **Cloud Storage**: Store quiz data, user profiles, and analytics in the cloud for easy access and scalability.
```

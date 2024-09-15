# **Requirements**:

1.  **Real-time Quiz Participation**:

    -   Users will connect to the Quiz Service via WebSocket with a unique quiz ID.
    -   When connected, the system ensures the user is part of the quiz session and ready to receive real-time updates.
2.  **Real-time Score Updates**:

    -   Once the user submits an answer, the server immediately calculates the score and broadcasts the updated score to the client.
    -   The server uses efficient message passing (via WebSocket or Redis Pub/Sub) to ensure low-latency updates for all connected users.
3.  **Real-time Leaderboard**:

    -   The Leaderboard Service subscribes to updates from the Quiz Service.
    -   Every time a score changes, the Leaderboard Service recalculates the rankings and broadcasts the updated leaderboard to all participants.
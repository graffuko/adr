Status
    Accepted

Context
    The app requires real-time updates for tracking the locations of drivers and passengers. The communication mechanism should support low-latency updates and be scalable.

Decision
    WebSocket will be used for real time communication

Rationale
    Real Time Updates
        Provides low-latency real-time communication, essential for tracking live locations.
    Simplicity
        Easier to implement and maintain compared to server-sent events, ensuring efficient real-time communication.

Consequences
    WHat this AD makes easier is it provides low latency real-time communication between the client and the server.

    What this AD makes more difficult is it requires additional infrastructure to handle WebSocket and it can be complex to scale.
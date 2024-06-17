Status
    Accepted

Context
    The app requires real-time updates for tracking drivers and passengers, necessitating a backend capable of handling asynchronous operations efficiently. The backend should be scalable and able to support high concurrency.

Decision
    Node.js will be used

Rational
    Asynchronous Handling
        Node.js is well-suited for handling asynchronous operations, which is crucial for real-time updates.
    Community and Ecosystem
        Large ecosystem of libraries and tools, making it easier to find resources and extend functionality.
    Performance
        Efficient handling of multiple connections, crucial for real-time capabilities, and scalable to handle high traffic.

Consequences
    What the AD makes easier is efficient handling of asynchronous operations, a large ecosystem of libraries and tools, and it is scalable for real time updates.

    What the AD makes more difficult is JavaScript's single threaded nature can be a limitation for CPU intensive tasks.


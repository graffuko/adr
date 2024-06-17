Status
    Accepted

Context
    The app requires secure authentication and authorization for both drivers and passengers. The system should support various authentication mechanisms and ensure proper authorization.

Decision
    Firebase Authentication with JWT will be used for authentication and authorization

Rationale
    Security
        Strong authentication mechanisms, ensuring secure access to the app.
    Ease of Integration
        Seamless integration with other Firebase services, simplifying development.
    Scalability
        Handles large user bases efficiently, supporting future growth.

Consequences
    What this AD makes easier is the integration with other Firebase services. It can handle large user bases efficiently and has strong security mechanisms.

    What this AD makes more difficult is it's dependency on Firebase's infrastructure. This may require some additional customization for specific security requirements.
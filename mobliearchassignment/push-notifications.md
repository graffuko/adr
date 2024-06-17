Status
    Accepted

Context
    The app needs to notify users about ride confirmations, driver updates, and important announcements. The notification service should support both iOS and Android platforms.

Decision
    Firebase Cloud Messaging will be used for push notifications

Rationale
    Cross-Platform Support
        Supports both iOS and Android, ensuring all users receive notifications.
    Features
        Offers personalization and message targeting, enhancing user engagement.
    Integration
        Easy integration with Firebase Authentication and other services, streamlining development.

Consequences
    What this AD makes easier is it supports both iOS and Android. It also offers personalization and messaging targeting. It also easily integrates with Firebase Authentication and other services.

    What this AD makes more difficult is it is dependent on Google. There also could be limitations in advanced notification features in comparison to dedicated services.
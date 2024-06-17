Status
    Accepted

Context
    The transportation company requires a mobile app that provides booking, tracking, and payment services. The app must be available on both iOS and Android platforms with consistent user experience and efficient development timelines. The app should also be cost effective to develop and maintain

Decision
    The app will be a hybrid app developed using React Native

Rationale
    Performance
        React Native provides near-native performance, essential for smooth user experiences in booking and tracking rides
    Development Speed
        Hybrid development allows code reuse across iOS and Android, speeding up development and reducing costs.
    Community and Support
        React Native has a large community and extensive documentation, ensuring we can find solutions and support quickly.
    UI Consistency
        Ensures a consistent user experience across both platforms, which is crucial for brand consistency and user satisfaction.

Consequences
    What becomes easier by making this change is development and maintenance are made easier because it is all under a single codebase. This also allows for faster development and deployment across both platforms

    What becomes more difficult by making this change is the app may face performance limitations compared to fully native apps. Because of certain complex native functionalities, there may need to be additional native code.
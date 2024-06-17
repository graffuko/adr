Status
    Accepted

Context
    The app needs to handle permissions for accessing geolocation, notifications, and other sensitive data on both iOS and Android platforms. The solution should ensure seamless and secure handling of permissions.

Decision
    React Native's built in permissions module and libraries will be used

Rationale
    Ease of Use
        Simplifies handling of platform-specific permissions, reducing development time and complexity.
    Community Support
        Well-documented and widely used within the React Native community, ensuring reliability and support.

Consequences
    What this AD makes easier is it simplifies the handling of platform specific permissions, overall reducing development times.

    What this AD makes more difficult is that it is limited to the functionalities provided by the libraries and may require additional native code in specific scenarios.
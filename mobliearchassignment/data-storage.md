Status
    Accepted

Context
    The app needs to store user profiles, ride history, and payment information efficiently and securely. The database should support high scalability and flexible schema design to accommodate future changes.

Decision
    MongoDB will be used for the database

Rationale
    Scalability
        Handles large volumes of data and scales horizontally, crucial for handling growing user data and ride history.
    Flexibility
        Schema-less design allows for flexible data modeling, accommodating changes in the data structure without major disruptions.
    Performance
        Suitable for read-heavy operations, ensuring quick retrieval of user profiles and ride history.

Consequences
    What this AD makes easier is the design is schemaless which allows for flexible data modeling. It also can handle large volumes of data and it scales horizontally.

    What this AD makes more difficult is it lacks the consistency guarantees of SQL databases. It needs to be carefully designed to ensure data integrity
#note

Class Diagram

Association 
    Person -> Address
Inheritance
    Cat -> <<interface>> Animal
Realization / Implement
    SMSNotifier -> <<interface>> Notifier
    EmailNotifier -> <<interface>> Notifier
Dependency
    Worker -> Tool 
Aggregation
    Category -> Post (when post is deleted, category is not deleted)
Composite
    Image -> Post (when post is deleted, image is also deleted)


Employee 1..*----1 Company

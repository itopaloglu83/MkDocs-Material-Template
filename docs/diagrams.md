# UML Diagrams

[PlantUML](https://plantuml.com) is used to create various UML diagrams.

## PlantUML

PlantUML code describes how a diagram should look like. This information then converted into a PNG image and added into the webpagee as a base64 inline image. Conversation is done via PlantUML web service.

### Sequence Diagram

A sequence diagram shows object interactions arranged in time sequence. It depicts the objects and classes involved in the scenario and the sequence of messages exchanged between the objects needed to carry out the functionality of the scenario.

=== "UML Diagram"

    ```plantuml
    @startuml
    title Authentication Sequence
    Alice -> Bob: Authentication Request
    Bob --> Alice: Authentication Response
    Alice -> Bob: Another authentication Request
    Alice <-- Bob: Another authentication Response
    @enduml
    ```

=== "PlantUML Code"

    ```
    @startuml
    title Authentication Sequence
    Alice -> Bob: Authentication Request
    Bob --> Alice: Authentication Response
    Alice -> Bob: Another authentication Request
    Alice <-- Bob: Another authentication Response
    @enduml
    ```

### Use Case Diagram

A use case diagram at its simplest is a representation of a user's interaction with the system that shows the relationship between the user and the different use cases in which the user is involved. A use case diagram can identify the different types of users of a system and the different use cases and will often be accompanied by other types of diagrams as well.

=== "UML Diagram"

    ```plantuml
    @startuml
    title Checkout Use Case
    left to right direction
    skinparam packageStyle rectangle
    actor customer
    actor clerk
    rectangle Checkout {
        customer -- (checkout)
        (checkout) .> (payment) : include
        (help) .> (checkout) : extends
        (checkout) -- clerk
    }
    @enduml
    ```

=== "PlantUML Code"

    ```
    @startuml
    title Checkout Use Case
    left to right direction
    skinparam packageStyle rectangle
    actor customer
    actor clerk
    rectangle Checkout {
        customer -- (checkout)
        (checkout) .> (payment) : include
        (help) .> (checkout) : extends
        (checkout) -- clerk
    }
    @enduml
    ```

### Activity Diagram

Activity diagrams are graphical representations of workflows of stepwise activities and actions with support for choice, iteration and concurrency.

=== "UML Diagram"

    ```plantuml
    @startuml
    title Diagram Generation Activity
    start
    repeat
    :read data;
    :generate diagrams;
    repeat while (more data?) is (yes)
    ->no;
    stop
    @enduml
    ```

=== "PlantUML Code"

    ```
    @startuml
    title Diagram Generation Activity
    start
    repeat
    :read data;
    :generate diagrams;
    repeat while (more data?) is (yes)
    ->no;
    stop
    @enduml
    ```

### Online Editor

PlantUML website also host an [online demo server](http://www.plantuml.com/plantuml/) which allows users to experiment with diagrams.

### Language Reference Guide

More information can be found at PlantUML [website](https://plantuml.com) and [language reference guide](http://pdf.plantuml.net/PlantUML_Language_Reference_Guide_en.pdf).


== Energy Monitor Setup

This monitoring system is current transformation (`CT`) clamp based implementation. CT technology is based on `Faraday` (Feh.ruh.dei) low. (Same theory behind the generator)

=== What have I used in this setup


=== Current Abilities
    Monitor and capture energy usage at the breaker level

=== Future Enhancements


[plantuml, plantuml-example, svg]
----
@startuml
:Main Admin: as Admin
(Use the application) as (Use)

User -> (Start)
User --> (Use)

Admin ---> (Use)

note right of Admin : This is an example.

note right of (Use)
  A note can also
  be on several lines
end note

note "This note is connected\nto several objects." as N2
(Start) .. N2
N2 .. (Use)
@enduml
----
# PersonId

![PersonId Diagram](../diagrams/Person__PersonId.dot.svg)

<a href="../../diagrams/Person__PersonId.dot.svg">Open interactive PersonId diagram</a>

## Formalization for PersonId

| Property | Constraint |
|----------|------------|
| genericproperties::hasIdentifier | exactly 1 owl::Thing |
| hasIDType | all IDType |
| issuedBy | max 1 owl::Thing |
| photoID | max 1 owl::Thing |
| subClassOf | PersonOntologyThing |
| validityPeriod | max 1 owl::Thing |

## Used by classes

| Class | Property |
|-------|----------|
| [Person (Person)](Person__Person.md) | hasPersonID |


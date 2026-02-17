![Draft for review only](/assets/img/draft_for_review.svg)

# PersonId

![PersonId Diagram](diagrams/PersonId.dot.svg)

<a href="diagrams/PersonId.dot.svg">Open interactive PersonId diagram</a>

## Formalization for PersonId

| Property | Constraint |
|----------|------------|
| cdm1:hasIdentifier | exactly 1 owl:Thing |
| hasIDType | all IDType |
| issuedBy | max 1 owl:Thing |
| photoID | max 1 owl:Thing |
| subClassOf | PersonThing |
| validityPeriod | max 1 owl:Thing |

## Used by classes

| Class | Property |
|-------|----------|
| [Person](Person.md) | hasPersonID |


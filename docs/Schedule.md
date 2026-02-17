![Draft for review only](/assets/img/draft_for_review.svg)

# Schedule

![Schedule Diagram](diagrams/Schedule.dot.svg)

<a href="diagrams/Schedule.dot.svg">Open interactive Schedule diagram</a>

## Formalization for Schedule

| Property | Constraint |
|----------|------------|
| cdm1:hasDescription | max 1 owl:Thing |
| cdm1:hasIdentifier | max 1 owl:Thing |
| cdm1:hasName | max 1 owl:Thing |
| cdm1:properPartOf | exactly 1 owl:Thing |
| hasClause | all Clause |
| subClassOf | BylawThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Law](Law.md) | hasSchedule |


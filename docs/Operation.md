![Draft for review only](/assets/img/draft_for_review.svg)

# Operation

![Operation Diagram](diagrams/Operation.dot.svg)

<a href="diagrams/Operation.dot.svg">Open interactive Operation diagram</a>

## Formalization for Operation

| Property | Constraint |
|----------|------------|
| hasClosingTime | max 1 owl:Thing |
| hasOpeningTime | max 1 owl:Thing |
| subClassOf | cdm1:RecurringEvent |
| subClassOf | CityOrgThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Organization](Organization.md) | operatingHours |


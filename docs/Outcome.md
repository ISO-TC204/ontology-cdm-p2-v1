![Draft for review only](/assets/img/draft_for_review.svg)

# Outcome

![Outcome Diagram](diagrams/Outcome.dot.svg)

<a href="diagrams/Outcome.dot.svg">Open interactive Outcome diagram</a>

## Formalization for Outcome

| Property | Constraint |
|----------|------------|
| cdm1:hasDescription | max 1 owl:Thing |
| fromPerspectiveOf | exactly 1 owl:Thing |
| hasBeneficialStakeholder | exactly 1 owl:Thing |
| hasImportance | max 1 owl:Thing |
| hasIndicator | all i72:Indicator |
| intendedImpact | max 1 owl:Thing |
| subClassOf | CityServiceThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Program](Program.md) | hasOutcome |
| [Service](Service.md) | hasOutcome |


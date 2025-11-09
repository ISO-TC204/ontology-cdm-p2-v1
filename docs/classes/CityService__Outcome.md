# Outcome

![Outcome Diagram](../diagrams/CityService__Outcome.dot.svg)

<a href="../../diagrams/CityService__Outcome.dot.svg">Open interactive Outcome diagram</a>

## Formalization for Outcome

| Property | Constraint |
|----------|------------|
| fromPerspectiveOf | exactly 1 owl::Thing |
| genProp::hasDescription | max 1 owl::Thing |
| hasBeneficialStakeholder | exactly 1 owl::Thing |
| hasImportance | max 1 owl::Thing |
| hasIndicator | all iso21972::Indicator |
| intendedImpact | max 1 owl::Thing |
| subClassOf | CityServiceOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Program (CityService)](CityService__Program.md) | hasOutcome |
| [Service (CityService)](CityService__Service.md) | hasOutcome |


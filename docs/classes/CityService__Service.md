# Service

![Service Diagram](../diagrams/CityService__Service.dot.svg)

<a href="../../diagrams/CityService__Service.dot.svg">Open interactive Service diagram</a>

## Formalization for Service

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 owl::Thing |
| genProp::hasName | max 1 owl::Thing |
| hasBeneficialStakeholder | all Stakeholder |
| hasContributingStakeholder | all Stakeholder |
| hasInput | all Input |
| hasOutcome | all Outcome |
| hasOutput | all Output |
| subClassOf | CityServiceOntologyThing |
| subClassOf | activity::Activity |

## Used by classes

| Class | Property |
|-------|----------|
| [Program (CityService)](CityService__Program.md) | hasService |


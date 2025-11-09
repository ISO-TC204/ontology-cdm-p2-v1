# Program

![Program Diagram](../diagrams/CityService__Program.dot.svg)

<a href="../../diagrams/CityService__Program.dot.svg">Open interactive Program diagram</a>

## Formalization for Program

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 owl::Thing |
| genProp::hasName | max 1 owl::Thing |
| hasBeneficialStakeholder | all Stakeholder |
| hasContributingStakeholder | all Stakeholder |
| hasInput | all Input |
| hasOutcome | all Outcome |
| hasOutput | all Output |
| hasService | all Service |
| subClassOf | CityServiceOntologyThing |
| subClassOf | activity::Activity |


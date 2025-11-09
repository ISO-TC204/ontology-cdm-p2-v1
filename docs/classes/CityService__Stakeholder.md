# Stakeholder

![Stakeholder Diagram](../diagrams/CityService__Stakeholder.dot.svg)

<a href="../../diagrams/CityService__Stakeholder.dot.svg">Open interactive Stakeholder diagram</a>

## Formalization for Stakeholder

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | all xsd::string |
| genProp::hasName | max 1 owl::Thing |
| hasCatchmentArea | all spatialloc::Location |
| hasCatchmentAreaType | all CatchmentAreaType |
| performs | some activity::Activity |
| subClassOf | CityServiceOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Input (CityService)](CityService__Input.md) | hasContributingStakeholder |
| [Program (CityService)](CityService__Program.md) | hasBeneficialStakeholder |
| [Program (CityService)](CityService__Program.md) | hasContributingStakeholder |
| [Service (CityService)](CityService__Service.md) | hasBeneficialStakeholder |
| [Service (CityService)](CityService__Service.md) | hasContributingStakeholder |


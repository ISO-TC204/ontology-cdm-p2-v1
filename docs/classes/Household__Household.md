# Household

![Household Diagram](../diagrams/Household__Household.dot.svg)

<a href="../../diagrams/Household__Household.dot.svg">Open interactive Household diagram</a>

## Formalization for Household

| Property | Constraint |
|----------|------------|
| cdmOrg::hasMember | all person::Person |
| householdOccupies | max 1 owl::Thing |
| subClassOf | HouseholdOntologyThing |
| time::hasTime | all time::ProperInterval |


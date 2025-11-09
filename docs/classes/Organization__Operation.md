# Operation

![Operation Diagram](../diagrams/Organization__Operation.dot.svg)

<a href="../../diagrams/Organization__Operation.dot.svg">Open interactive Operation diagram</a>

## Formalization for Operation

| Property | Constraint |
|----------|------------|
| closingTime | max 1 owl::Thing |
| openingTime | max 1 owl::Thing |
| subClassOf | resource::RecurringEvent |
| subClassOf | CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Organization (Organization)](Organization__Organization.md) | operatingHours |


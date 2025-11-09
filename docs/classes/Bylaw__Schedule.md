# Schedule

![Schedule Diagram](../diagrams/Bylaw__Schedule.dot.svg)

<a href="../../diagrams/Bylaw__Schedule.dot.svg">Open interactive Schedule diagram</a>

## Formalization for Schedule

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 owl::Thing |
| genProp::hasIdentifier | max 1 owl::Thing |
| genProp::hasName | max 1 owl::Thing |
| hasClause | all Clause |
| partwhole::properPartOf | exactly 1 owl::Thing |
| subClassOf | BylawOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Law (Bylaw)](Bylaw__Law.md) | hasSchedule |


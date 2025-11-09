# Clause

![Clause Diagram](../diagrams/Bylaw__Clause.dot.svg)

<a href="../../diagrams/Bylaw__Clause.dot.svg">Open interactive Clause diagram</a>

## Formalization for Clause

| Property | Constraint |
|----------|------------|
| clauseType | some Enum: bylaw, penalty, repeal, schedule, severance, transition |
| genProp::hasDescription | max 1 owl::Thing |
| genProp::hasIdentifier | max 1 owl::Thing |
| genProp::hasName | max 1 owl::Thing |
| hasClause | all Clause |
| partwhole::properPartOf | exactly 1 owl::Thing |
| subClassOf | BylawOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Clause (Bylaw)](Bylaw__Clause.md) | hasClause |
| [Law (Bylaw)](Bylaw__Law.md) | hasClause |
| [Law (Bylaw)](Bylaw__Law.md) | hasPenaltyClause |
| [Law (Bylaw)](Bylaw__Law.md) | hasRepealClause |
| [Law (Bylaw)](Bylaw__Law.md) | hasSeveranceClause |
| [Law (Bylaw)](Bylaw__Law.md) | hasTransitionClause |
| [Schedule (Bylaw)](Bylaw__Schedule.md) | hasClause |


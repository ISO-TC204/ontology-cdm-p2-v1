![Draft for review only](/assets/img/draft_for_review.svg)

# Clause

![Clause Diagram](diagrams/Clause.dot.svg)

<a href="diagrams/Clause.dot.svg">Open interactive Clause diagram</a>

## Formalization for Clause

| Property | Constraint |
|----------|------------|
| cdm1:hasDescription | max 1 owl:Thing |
| cdm1:hasIdentifier | max 1 owl:Thing |
| cdm1:hasName | max 1 owl:Thing |
| cdm1:properPartOf | exactly 1 owl:Thing |
| clauseType | some Enum: bylaw, penalty, repeal, schedule, severance, transition |
| hasClause | all Clause |
| subClassOf | BylawThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Clause](Clause.md) | hasClause |
| [Law](Law.md) | hasClause |
| [Law](Law.md) | hasPenaltyClause |
| [Law](Law.md) | hasRepealClause |
| [Law](Law.md) | hasSeveranceClause |
| [Law](Law.md) | hasTransitionClause |
| [Schedule](Schedule.md) | hasClause |


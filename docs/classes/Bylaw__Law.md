# Law

![Law Diagram](../diagrams/Bylaw__Law.dot.svg)

<a href="../../diagrams/Bylaw__Law.dot.svg">Open interactive Law diagram</a>

## Specializations of Law

| Class | Description |
|-------|-------------|
| [Amending Bylaw (Bylaw)](Bylaw__AmendingBylaw.md) |  |
| [Bylaw (Bylaw)](Bylaw__Bylaw.md) |  |
| [Main Bylaw (Bylaw)](Bylaw__MainBylaw.md) |  |
| [Revision Bylaw (Bylaw)](Bylaw__RevisionBylaw.md) |  |

## Formalization for Law

| Property | Constraint |
|----------|------------|
| abstract | max 1 owl::Thing |
| dateInEffect | max 1 owl::Thing |
| datePublished | max 1 owl::Thing |
| expires | max 1 owl::Thing |
| genProp::hasName | all xsd::string |
| hasClause | all Clause |
| hasDefinition | all Definition |
| hasPenaltyClause | all Clause |
| hasRepealClause | all Clause |
| hasSchedule | all Schedule |
| hasSeveranceClause | all Clause |
| hasTransitionClause | all Clause |
| keywords | all xsd::string |
| legislationDate | max 1 owl::Thing |
| legislationIdentifier | max 1 owl::Thing |
| legislationJurisdiction | max 1 owl::Thing |
| legislationLegalForce | all Enum: InForce, NotInForce, PartiallyInForce |
| subClassOf | BylawOntologyThing |


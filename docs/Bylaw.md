![Draft for review only](/assets/img/draft_for_review.svg)

# Bylaw

NOTE: Higher levels of government often place limits on what laws can be passed by lower-level entities.

![Bylaw Diagram](diagrams/Bylaw.dot.svg)

<a href="diagrams/Bylaw.dot.svg">Open interactive Bylaw diagram</a>

## Specializations of Bylaw

| Class | Description |
|-------|-------------|
| [Amending Bylaw](AmendingBylaw.md) |  |
| [Main Bylaw](MainBylaw.md) |  |
| [Revision Bylaw](RevisionBylaw.md) |  |

## Formalization for Bylaw

| Property | Constraint |
|----------|------------|
| impacts | all JurisdictionalArea or LandArea or Organization or Person or cdm1:Activity |
| legislationJurisdiction | max 1 owl:Thing |
| legislationType | all Enum: amendingBylaw, mainBylaw, revisionBylaw |
| subClassOf | Law |

## Used by classes

| Class | Property |
|-------|----------|
| [Jurisdictional Area (TransportInfrastructurePattern)](JurisdictionalArea.md) | hasBylaw |


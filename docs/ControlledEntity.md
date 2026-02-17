![Draft for review only](/assets/img/draft_for_review.svg)

# ControlledEntity

![ControlledEntity Diagram](diagrams/ControlledEntity.dot.svg)

<a href="diagrams/ControlledEntity.dot.svg">Open interactive ControlledEntity diagram</a>

## Specializations of ControlledEntity

| Class | Description |
|-------|-------------|
| [Entity Operation](EntityOperation.md) |  |
| [Entity Ownership](EntityOwnership.md) |  |

## Formalization for ControlledEntity

| Property | Constraint |
|----------|------------|
| entity | some owl:Thing |
| subClassOf | CityResidentThing |
| time:hasTime | max 1 owl:Thing |


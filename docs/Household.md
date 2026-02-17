![Draft for review only](/assets/img/draft_for_review.svg)

# Household

NOTE: More precise definitions of Household may be adopted as required for different contexts and applications through extensions to this class.

![Household Diagram](diagrams/Household.dot.svg)

<a href="diagrams/Household.dot.svg">Open interactive Household diagram</a>

## Formalization for Household

| Property | Constraint |
|----------|------------|
| householdOccupies | max 1 owl:Thing |
| org:hasMember | all Person |
| subClassOf | HouseholdThing |
| time:hasTime | all time:ProperInterval |


![Draft for review only](/assets/img/draft_for_review.svg)

# LandArea

![LandArea Diagram](diagrams/LandArea.dot.svg)

<a href="diagrams/LandArea.dot.svg">Open interactive LandArea diagram</a>

## Formalization for LandArea

| Property | Constraint |
|----------|------------|
| cdm1:hasDescription | all xsd:string |
| hasArea | all cdm1:Area |
| hasPopulation | all i72:Population |
| landUse | all LandUseClassification |
| subClassOf | cdm1:Location |
| subClassOf | LandUseThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Jurisdictional Area (TransportInfrastructurePattern)](JurisdictionalArea.md) | hasLandArea |


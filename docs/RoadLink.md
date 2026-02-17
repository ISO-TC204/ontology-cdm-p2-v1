![Draft for review only](/assets/img/draft_for_review.svg)

# RoadLink

![RoadLink Diagram](diagrams/RoadLink.dot.svg)

<a href="diagrams/RoadLink.dot.svg">Open interactive RoadLink diagram</a>

## Formalization for RoadLink

| Property | Constraint |
|----------|------------|
| cdm1:aggregateOf | all Road |
| subClassOf | TravelledWayLink |

## Used by classes

| Class | Property |
|-------|----------|
| [Road](Road.md) | cdm1:aggregationOf |
| [Road Segment](RoadSegment.md) | cdm1:properPartOf |


# Output

![Output Diagram](../diagrams/CityService__Output.dot.svg)

<a href="../../diagrams/CityService__Output.dot.svg">Open interactive Output diagram</a>

## Formalization for Output

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | all xsd::string |
| genProp::hasName | max 1 owl::Thing |
| subClassOf | CityServiceOntologyThing |
| subClassOf | resource::TerminalResourceState |
| usedByIndicator | all iso21972::Indicator |

## Used by classes

| Class | Property |
|-------|----------|
| [Program (CityService)](CityService__Program.md) | hasOutput |
| [Service (CityService)](CityService__Service.md) | hasOutput |


# Definition

![Definition Diagram](../diagrams/Bylaw__Definition.dot.svg)

<a href="../../diagrams/Bylaw__Definition.dot.svg">Open interactive Definition diagram</a>

## Formalization for Definition

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 owl::Thing |
| genProp::hasName | max 1 owl::Thing |
| partwhole::properPartOf | exactly 1 owl::Thing |
| subClassOf | BylawOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Law (Bylaw)](Bylaw__Law.md) | hasDefinition |


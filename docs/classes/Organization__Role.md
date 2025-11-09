# Role

![Role Diagram](../diagrams/Organization__Role.dot.svg)

<a href="../../diagrams/Organization__Role.dot.svg">Open interactive Role diagram</a>

## Formalization for Role

| Property | Constraint |
|----------|------------|
| hasGoal | all Goal |
| hasProcess | all activity::Activity |
| hasResource | all resource1::Resource |
| subClassOf | org::Role |
| subClassOf | CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Organization Agent (Organization)](Organization__OrganizationAgent.md) | playsRole |


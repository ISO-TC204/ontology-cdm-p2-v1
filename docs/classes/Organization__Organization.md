# Organization

![Organization Diagram](../diagrams/Organization__Organization.dot.svg)

<a href="../../diagrams/Organization__Organization.dot.svg">Open interactive Organization diagram</a>

## Specializations of Organization

| Class | Description |
|-------|-------------|
| [For Profit Organization (Organization)](Organization__ForProfitOrganization.md) |  |
| [Government Organization (Organization)](Organization__GovernmentOrganization.md) |  |
| [Non Profit Organization (Organization)](Organization__NonProfitOrganization.md) |  |

## Formalization for Organization

| Property | Constraint |
|----------|------------|
| contact::hasTelephone | all contact::PhoneNumber |
| hasGoal | all Goal |
| operatingHours | all Operation |
| orgAddress | all contact::Address |
| spatialLoc::hasLocation | all spatialLoc::Location |
| subClassOf | cdmOrgStruct::Organization |
| subClassOf | CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Employment (Organization)](Organization__Employment.md) | employedBy |
| [Organization Agent (Organization)](Organization__OrganizationAgent.md) | org::memberOf |


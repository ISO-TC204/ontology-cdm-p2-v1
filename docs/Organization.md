![Draft for review only](/assets/img/draft_for_review.svg)

# Organization

![Organization Diagram](diagrams/Organization.dot.svg)

<a href="diagrams/Organization.dot.svg">Open interactive Organization diagram</a>

## Specializations of Organization

| Class | Description |
|-------|-------------|
| [For Profit Organization](ForProfitOrganization.md) |  |
| [Government Organization](GovernmentOrganization.md) |  |
| [Non Profit Organization](NonProfitOrganization.md) |  |

## Formalization for Organization

| Property | Constraint |
|----------|------------|
| cdm1:hasLocation | all cdm1:Location |
| hasGoal | all Goal |
| hasTelephone | all PhoneNumber |
| operatingHours | all Operation |
| orgAddress | all Address |
| subClassOf | cdm1:Organization |
| subClassOf | CityOrgThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Employment](Employment.md) | employedBy |
| [Organization Agent](OrganizationAgent.md) | org:memberOf |


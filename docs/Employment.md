![Draft for review only](/assets/img/draft_for_review.svg)

# Employment

![Employment Diagram](diagrams/Employment.dot.svg)

<a href="diagrams/Employment.dot.svg">Open interactive Employment diagram</a>

## Formalization for Employment

| Property | Constraint |
|----------|------------|
| employedAs | all Occupation |
| employedBy | some Organization |
| hasCompensation | some Compensation |
| hasEmploymentStatus | all EmploymentStatus |
| subClassOf | CityOrgThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Organization Agent](OrganizationAgent.md) | hasEmployment |


![Draft for review only](/assets/img/draft_for_review.svg)

# OrganizationAgent

NOTE: Organization Agents have goals, authority, and may be members of some team.

![OrganizationAgent Diagram](diagrams/OrganizationAgent.dot.svg)

<a href="diagrams/OrganizationAgent.dot.svg">Open interactive OrganizationAgent diagram</a>

## Formalization for OrganizationAgent

| Property | Constraint |
|----------|------------|
| hasEmployment | all Employment |
| hasGoal | all Goal |
| org:memberOf | all Organization |
| playsRole | all Role |
| subClassOf | cdm1:Agent |
| subClassOf | CityOrgThing |


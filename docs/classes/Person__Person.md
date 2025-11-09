# Person

![Person Diagram](../diagrams/Person__Person.dot.svg)

<a href="../../diagrams/Person__Person.dot.svg">Open interactive Person diagram</a>

## Formalization for Person

| Property | Constraint |
|----------|------------|
| alias | all PersonName |
| birthDate | max 1 owl::Thing |
| birthplace | max 1 owl::Thing |
| children | all Person |
| citizenOf | all Citizenship |
| contact::email | all xsd::string |
| contact::hasAddress | all contact::Address |
| contact::hasTelephone | all contact::PhoneNumber |
| deathDate | max 1 owl::Thing |
| deathPlace | max 1 owl::Thing |
| hasEducation | all Education |
| hasGenderIdentity | all Gender |
| hasPersonID | all PersonId |
| hasSkill | all Skill |
| income | all cityUnits::MonetaryValue |
| name | max 1 owl::Thing |
| parent | all Person |
| sex | max 1 owl::Thing |
| spouse | all Person |
| subClassOf | PersonOntologyThing |
| subClassOf | agent::Agent |

## Used by classes

| Class | Property |
|-------|----------|
| [Person (Person)](Person__Person.md) | children |
| [Person (Person)](Person__Person.md) | parent |
| [Person (Person)](Person__Person.md) | spouse |


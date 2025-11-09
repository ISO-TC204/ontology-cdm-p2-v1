# JurisdictionalArea

![JurisdictionalArea Diagram](../diagrams/City__JurisdictionalArea.dot.svg)

<a href="../../diagrams/City__JurisdictionalArea.dot.svg">Open interactive JurisdictionalArea diagram</a>

## Specializations of JurisdictionalArea

| Class | Description |
|-------|-------------|
| [City (City)](City__City.md) |  |
| [City Administrative Area (City)](City__CityAdministrativeArea.md) |  |

## Formalization for JurisdictionalArea

| Property | Constraint |
|----------|------------|
| administrativeAreaOf | all JurisdictionalArea |
| bylaw::hasBylaw | all bylaw::Bylaw |
| genericproperties::hasName | max 1 owl::Thing |
| hasGovernment | all organization::GovernmentOrganization |
| inverse administrativeAreaOf | all JurisdictionalArea |
| landUse::hasLandArea | all landUse::LandArea |
| landUse::residentPopulation | max 1 owl::Thing |
| subClassOf | CityOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Jurisdictional Area (City)](City__JurisdictionalArea.md) | administrativeArea |
| [Jurisdictional Area (City)](City__JurisdictionalArea.md) | administrativeAreaOf |


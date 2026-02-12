![Draft for review only](/assets/img/draft_for_review.svg)

# ontology-cdm-p2

## Untitled Ontology

This ontology specifies the city-level concepts for the city pattern of the city data model. The City pattern captures basic information about the geospatial aspects of the city.  In particular it represents the different ways in which the city is administratively divided.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [City Pattern Thing (CityPattern)](classes/CityPattern__CityPatternThing.md)

The formal definition of these patterns is available in [OWL Syntax](CityPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the transport infrastructure pattern of the city data model. The Transportation Infrastructure pattern defines the concepts that are relevant in describing the physical transportation infrastructure and their characteristics. This includes the concepts of a Road, Bridge, and Tunnel. The Infrastructure Pattern is reused here, as these transportation structures are all defined as types of (subclasses) Infrastructure Elements.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](TransportInfrastructurePattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the building pattern of the city data model. A Building is a structure with some location in the urban system. The location of the Building in space may change due to construction, but the Parcel/Lot of land it is located on cannot. There may be many different types (subclasses) of buildings, such as House, Apartment Building, Office Building, and so on.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](BuildingPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the land use pattern of the city data model. The Land Use Pattern captures concepts related to land use and cover over time. Land Use Classifications provide a means of describing the land cover/use in a standard way. Various classification systems are used to identify types of land use. Currently, we include LBCS, CLUMP, and AAFC. The ontology reuses and extends the Land Based Classification Standards (LBCS) Ontology  presented by (Montenegro, Gomes, Urbano, and Duarte, 2011) for this purpose.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](LandUsePattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the code pattern of the city data model. The Code Pattern provides a structure to address the challenge of value enumeration with a general approach. In city data there are many classes of things that are intended to be instantiated using a set list of values (e.g., classification systems), however these values may change based on application or context. 
        The Code Pattern introduces a generic set of classes and properties that can be used to extend such classes to define various classification systems in an integrated way. Instead of enumerating value sets for classes, values can be defined with an associated Code that specifies additional metadata about the value and its origins.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](CodePattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the person pattern of the city data model.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](PersonPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the organization pattern of the city data model. The Organization pattern is an extension of the Organization Structure pattern defined in ISO/IEC 5087-1 that introduces city-specific concepts related to Organizations such as Students and Employees.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](OrganizationPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts of the city data model.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Address (5087-2)](classes/5087-2__Address.md)
- [Address Type (5087-2)](classes/5087-2__AddressType.md)
- [amending Bylaw (5087-2)](classes/5087-2__amendingBylaw.md)
- [Amending Bylaw (5087-2)](classes/5087-2__AmendingBylaw.md)
- [Area Ratio (5087-2)](classes/5087-2__AreaRatio.md)
- [Bridge (5087-2)](classes/5087-2__Bridge.md)
- [Bridge Segment (5087-2)](classes/5087-2__BridgeSegment.md)
- [Building (5087-2)](classes/5087-2__Building.md)
- [Building Thing (5087-2)](classes/5087-2__BuildingThing.md)
- [Building Unit (5087-2)](classes/5087-2__BuildingUnit.md)
- [Building Use (5087-2)](classes/5087-2__BuildingUse.md)
- [Business Establishment (5087-2)](classes/5087-2__BusinessEstablishment.md)
- [bylaw (5087-2)](classes/5087-2__bylaw.md)
- [Bylaw (5087-2)](classes/5087-2__Bylaw.md)
- [Bylaw Pattern Clause Type Enum (5087-2)](classes/5087-2__BylawPatternClauseTypeEnum.md)
- [Bylaw Pattern Legislation Legal Force Enum (5087-2)](classes/5087-2__BylawPatternLegislationLegalForceEnum.md)
- [Bylaw Pattern Legislation Type Enum (5087-2)](classes/5087-2__BylawPatternLegislationTypeEnum.md)
- [Bylaw Thing (5087-2)](classes/5087-2__BylawThing.md)
- [Catchment Area Type (5087-2)](classes/5087-2__CatchmentAreaType.md)
- [Citizenship (5087-2)](classes/5087-2__Citizenship.md)
- [City (5087-2)](classes/5087-2__City.md)
- [City Administrative Area (5087-2)](classes/5087-2__CityAdministrativeArea.md)
- [City Org Thing (5087-2)](classes/5087-2__CityOrgThing.md)
- [City Pattern Thing (5087-2)](classes/5087-2__CityPatternThing.md)
- [City Resident (5087-2)](classes/5087-2__CityResident.md)
- [City Resident Thing (5087-2)](classes/5087-2__CityResidentThing.md)
- [City Service Thing (5087-2)](classes/5087-2__CityServiceThing.md)
- [City Thing (5087-2)](classes/5087-2__CityThing.md)
- [Clause (5087-2)](classes/5087-2__Clause.md)
- [Code (5087-2)](classes/5087-2__Code.md)
- [Code Thing (5087-2)](classes/5087-2__CodeThing.md)
- [Compensation (5087-2)](classes/5087-2__Compensation.md)
- [Condition Precedent (5087-2)](classes/5087-2__ConditionPrecedent.md)
- [Construction Status (5087-2)](classes/5087-2__ConstructionStatus.md)
- [Contact Thing (5087-2)](classes/5087-2__ContactThing.md)
- [Contract (5087-2)](classes/5087-2__Contract.md)
- [Contract Thing (5087-2)](classes/5087-2__ContractThing.md)
- [Contractual Commitment (5087-2)](classes/5087-2__ContractualCommitment.md)
- [Contractual Definition (5087-2)](classes/5087-2__ContractualDefinition.md)
- [Contractual Element (5087-2)](classes/5087-2__ContractualElement.md)
- [Controlled Entity (5087-2)](classes/5087-2__ControlledEntity.md)
- [Country (5087-2)](classes/5087-2__Country.md)
- [Definition (5087-2)](classes/5087-2__Definition.md)
- [Education (5087-2)](classes/5087-2__Education.md)
- [Email Address (5087-2)](classes/5087-2__EmailAddress.md)
- [Employment (5087-2)](classes/5087-2__Employment.md)
- [Employment Status (5087-2)](classes/5087-2__EmploymentStatus.md)
- [Entity Operation (5087-2)](classes/5087-2__EntityOperation.md)
- [Entity Ownership (5087-2)](classes/5087-2__EntityOwnership.md)
- [Facility (5087-2)](classes/5087-2__Facility.md)
- [For Profit Organization (5087-2)](classes/5087-2__ForProfitOrganization.md)
- [Gender (5087-2)](classes/5087-2__Gender.md)
- [Goal (5087-2)](classes/5087-2__Goal.md)
- [Government Organization (5087-2)](classes/5087-2__GovernmentOrganization.md)
- [Home Type (5087-2)](classes/5087-2__HomeType.md)
- [Household (5087-2)](classes/5087-2__Household.md)
- [Household Thing (5087-2)](classes/5087-2__HouseholdThing.md)
- [ID Type (5087-2)](classes/5087-2__IDType.md)
- [Impact Direction (5087-2)](classes/5087-2__ImpactDirection.md)
- [Importance (5087-2)](classes/5087-2__Importance.md)
- [Industry Type (5087-2)](classes/5087-2__IndustryType.md)
- [In Force (5087-2)](classes/5087-2__InForce.md)
- [Infrastructure Element (5087-2)](classes/5087-2__InfrastructureElement.md)
- [Infrastructure Thing (5087-2)](classes/5087-2__InfrastructureThing.md)
- [Input (5087-2)](classes/5087-2__Input.md)
- [Jurisdictional Area (5087-2)](classes/5087-2__JurisdictionalArea.md)
- [Land Area (5087-2)](classes/5087-2__LandArea.md)
- [Land Use Classification (5087-2)](classes/5087-2__LandUseClassification.md)
- [Land Use Thing (5087-2)](classes/5087-2__LandUseThing.md)
- [Law (5087-2)](classes/5087-2__Law.md)
- [main Bylaw (5087-2)](classes/5087-2__mainBylaw.md)
- [Main Bylaw (5087-2)](classes/5087-2__MainBylaw.md)
- [Name (5087-2)](classes/5087-2__Name.md)
- [Non Binding Term (5087-2)](classes/5087-2__NonBindingTerm.md)
- [Non Profit Organization (5087-2)](classes/5087-2__NonProfitOrganization.md)
- [Not In Force (5087-2)](classes/5087-2__NotInForce.md)
- [Occupation (5087-2)](classes/5087-2__Occupation.md)
- [Operation (5087-2)](classes/5087-2__Operation.md)
- [Organization (5087-2)](classes/5087-2__Organization.md)
- [Organization Agent (5087-2)](classes/5087-2__OrganizationAgent.md)
- [Outcome (5087-2)](classes/5087-2__Outcome.md)
- [Output (5087-2)](classes/5087-2__Output.md)
- [Partially In Force (5087-2)](classes/5087-2__PartiallyInForce.md)
- [penalty (5087-2)](classes/5087-2__penalty.md)
- [Person (5087-2)](classes/5087-2__Person.md)
- [Person Id (5087-2)](classes/5087-2__PersonId.md)
- [Person Name (5087-2)](classes/5087-2__PersonName.md)
- [Person Thing (5087-2)](classes/5087-2__PersonThing.md)
- [Phone Number (5087-2)](classes/5087-2__PhoneNumber.md)
- [Phone Type (5087-2)](classes/5087-2__PhoneType.md)
- [Program (5087-2)](classes/5087-2__Program.md)
- [Rail Line (5087-2)](classes/5087-2__RailLine.md)
- [Rail Link (5087-2)](classes/5087-2__RailLink.md)
- [Rail Segment (5087-2)](classes/5087-2__RailSegment.md)
- [repeal (5087-2)](classes/5087-2__repeal.md)
- [Representation (5087-2)](classes/5087-2__Representation.md)
- [Residence (5087-2)](classes/5087-2__Residence.md)
- [Residential Relationship (5087-2)](classes/5087-2__ResidentialRelationship.md)
- [Revision Bylaw (5087-2)](classes/5087-2__RevisionBylaw.md)
- [revision Bylaw (5087-2)](classes/5087-2__revisionBylaw.md)
- [Road (5087-2)](classes/5087-2__Road.md)
- [Road Link (5087-2)](classes/5087-2__RoadLink.md)
- [Road Network Type (5087-2)](classes/5087-2__RoadNetworkType.md)
- [Road Segment (5087-2)](classes/5087-2__RoadSegment.md)
- [Role (5087-2)](classes/5087-2__Role.md)
- [Salary (5087-2)](classes/5087-2__Salary.md)
- [Schedule (5087-2)](classes/5087-2__Schedule.md)
- [schedule (5087-2)](classes/5087-2__schedule.md)
- [Service (5087-2)](classes/5087-2__Service.md)
- [severance (5087-2)](classes/5087-2__severance.md)
- [Sex (5087-2)](classes/5087-2__Sex.md)
- [Skill (5087-2)](classes/5087-2__Skill.md)
- [Stakeholder (5087-2)](classes/5087-2__Stakeholder.md)
- [State (5087-2)](classes/5087-2__State.md)
- [Street Direction (5087-2)](classes/5087-2__StreetDirection.md)
- [Street Type (5087-2)](classes/5087-2__StreetType.md)
- [transition (5087-2)](classes/5087-2__transition.md)
- [Transport Infrastructure Thing (5087-2)](classes/5087-2__TransportInfrastructureThing.md)
- [Travelled Way (5087-2)](classes/5087-2__TravelledWay.md)
- [Travelled Way Link (5087-2)](classes/5087-2__TravelledWayLink.md)
- [Travelled Way Segment (5087-2)](classes/5087-2__TravelledWaySegment.md)
- [Tunnel (5087-2)](classes/5087-2__Tunnel.md)
- [Tunnel Segment (5087-2)](classes/5087-2__TunnelSegment.md)
- [Wage (5087-2)](classes/5087-2__Wage.md)
- [Warranty (5087-2)](classes/5087-2__Warranty.md)
- [Year (5087-2)](classes/5087-2__Year.md)

The formal definition of these patterns is available in [OWL Syntax](5087-2.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the household pattern of the city data model. The Household pattern captures basic information about households within the city.  In particular it represents the different types and structures of households.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](HouseholdPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the infrastructure pattern of the city data model. The Infrastructure pattern defines the concepts needed to capture various types of city infrastructure, such as buildings and roads. The Infrastructure pattern reuses the Spatial Location pattern (from ISO 5087-1) in order to capture the location of these infrastructure elements.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](InfrastructurePattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the city resident pattern of the city data model. As different cities have different definitions of who is that city's Resident, the City Resident Pattern must contain the properties required by each.  Central to all of the definitions is the concept of residing. Variously referred to as a home or domicile in which the resident spends significant amounts of time.  They may own it, rent it or just stay in it.  Legally, “reside means to dwell permanently or continuously. It expresses an idea that a person keeps or returns to a particular dwelling place as his fixed, settled, or legal abode. The meaning of reside implies a continuous arrangement” ; reside has both a temporal and spatial dimension. The city of Toronto's definition of a city resident includes the concept of owning property or owning or operating a business in the city. For Beijing, nationality is a unique aspect.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](CityResidentPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the bylaw pattern of the city data model.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Bylaw Pattern Clause Type Enum (BylawPattern)](classes/BylawPattern__BylawPatternClauseTypeEnum.md)
- [Bylaw Pattern Legislation Legal Force Enum (BylawPattern)](classes/BylawPattern__BylawPatternLegislationLegalForceEnum.md)
- [Bylaw Pattern Legislation Type Enum (BylawPattern)](classes/BylawPattern__BylawPatternLegislationTypeEnum.md)

The formal definition of these patterns is available in [OWL Syntax](BylawPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the contact pattern of the city data model.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](ContactPattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts that are used by all other patterns of the city-level portion of the city data model.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](Core.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the city service pattern of the city data model. Cities provide a variety of services to residents and businesses, including health and social services. The city service ontology, is based on the Canadian Government Reference Model (CGRM). See Wiseman, R. (2015). Canadian Governments Reference Models. In Service Systems Science (pp. 109-128). Springer, Tokyo.

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](CityServicePattern.owl).

## Untitled Ontology

This ontology specifies the city-level concepts for the contract pattern of the city data model. A contract is a legal document that specifies some agreement(s) between two or more parties. The aim of the contract pattern is not to formalize the semantics of all possible involved legal concepts, but rather to enable to representation of the general structure and contents of a particular contract. The Contract Ontology adopts the definition of Contract specified in the Financial Business Ontology (FIBO) [8] specified at: https://spec.edmcouncil.org/fibo/ontology/FND/Agreements/Contracts/ with a key modification that a Contract is defined as a type of Document and is distinct from an Agreement (not a subclass, as specified in FIBO).

This ontology consists of the following patterns:


The formal definition of these patterns is available in [OWL Syntax](ContractPattern.owl).


# Information technology - City data model - Part 2: City level concepts - Contract pattern

This ontology specifies the city-level concepts for the contract pattern of the city data model. A contract is a legal document that specifies some agreement(s) between two or more parties. The aim of the contract pattern is not to formalize the semantics of all possible involved legal concepts, but rather to enable to representation of the general structure and contents of a particular contract. The Contract Ontology adopts the definition of Contract specified in the Financial Business Ontology (FIBO) [8] specified at: https://spec.edmcouncil.org/fibo/ontology/FND/Agreements/Contracts/ with a key modification that a Contract is defined as a type of Document and is distinct from an Agreement (not a subclass, as specified in FIBO).

This pattern imports the following files:

- [https://w3id.org/citydata/part1/v1/AgreementPattern](https://w3id.org/citydata/part1/v1/AgreementPattern)
- [https://w3id.org/citydata/part2/v1/OrganizationPattern](https://w3id.org/citydata/part2/v1/OrganizationPattern)

This pattern consists of the following classes:

- [Condition Precedent](ConditionPrecedent.md)
- [Contract](Contract.md)
- [Contract Thing](ContractThing.md)
- [Contractual Commitment](ContractualCommitment.md)
- [Contractual Definition](ContractualDefinition.md)
- [Contractual Element](ContractualElement.md)
- [Non Binding Term](NonBindingTerm.md)
- [Representation](Representation.md)
- [Warranty](Warranty.md)
This module defines the following properties:

- [ContractDataProperty](../properties/ContractDataProperty.md)
- [ContractObjectProperty](../properties/ContractObjectProperty.md)
- [contractualElementOf](../properties/contractualElementOf.md)
- [hasContract](../properties/hasContract.md)
- [hasContractText](../properties/hasContractText.md)
- [hasContractualElement](../properties/hasContractualElement.md)
- [hasParty](../properties/hasParty.md)
- [hasSignatory](../properties/hasSignatory.md)
- [isExecutedOn](../properties/isExecutedOn.md)
- [isValidFor](../properties/isValidFor.md)
- [specifiesAgreement](../properties/specifiesAgreement.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../ContractPattern.ttl) and the SHACL [restrictions](../ContractSHACL.ttl).

![Draft for review only](/assets/img/draft_for_review.svg)

# Contract Pattern

This ontology specifies the city-level concepts for the contract pattern of the city data model. A contract is a legal document that specifies some agreement(s) between two or more parties. The aim of the contract pattern is not to formalize the semantics of all possible involved legal concepts, but rather to enable to representation of the general structure and contents of a particular contract. The Contract Ontology adopts the definition of Contract specified in the Financial Business Ontology (FIBO) [8] specified at: https://spec.edmcouncil.org/fibo/ontology/FND/Agreements/Contracts/ with a key modification that a Contract is defined as a type of Document and is distinct from an Agreement (not a subclass, as specified in FIBO).

This pattern imports the following patterns:

- Agreement Pattern
- [Organization Pattern](OrganizationPattern.md)

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

The formal definition of this pattern is available in [OWL Syntax](ContractPattern.owl).


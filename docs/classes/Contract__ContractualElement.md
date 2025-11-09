# ContractualElement

![ContractualElement Diagram](../diagrams/Contract__ContractualElement.dot.svg)

<a href="../../diagrams/Contract__ContractualElement.dot.svg">Open interactive ContractualElement diagram</a>

## Specializations of ContractualElement

| Class | Description |
|-------|-------------|
| [Condition Precedent (Contract)](Contract__ConditionPrecedent.md) |  |
| [Contractual Commitment (Contract)](Contract__ContractualCommitment.md) |  |
| [Contractual Definition (Contract)](Contract__ContractualDefinition.md) |  |
| [Non Binding Term (Contract)](Contract__NonBindingTerm.md) |  |
| [Representation (Contract)](Contract__Representation.md) |  |
| [Warranty (Contract)](Contract__Warranty.md) |  |

## Formalization for ContractualElement

| Property | Constraint |
|----------|------------|
| hasContractText | some xsd::string |
| inverse hasContractualElement | some Contract |
| subClassOf | ContractOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Contract (Contract)](Contract__Contract.md) | hasContractualElement |


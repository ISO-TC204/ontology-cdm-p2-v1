# Contract

![Contract Diagram](../diagrams/Contract__Contract.dot.svg)

<a href="../../diagrams/Contract__Contract.dot.svg">Open interactive Contract diagram</a>

## Formalization for Contract

| Property | Constraint |
|----------|------------|
| executedOn | all time::TemporalEntity |
| hasContractualElement | some ContractualElement |
| hasParty | min 2 owl::Thing |
| hasSignatory | min 2 owl::Thing |
| isValidFor | all time::Interval |
| specifiesAgreement | some agreement::Agreement |
| subClassOf | ContractOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Contractual Element (Contract)](Contract__ContractualElement.md) | Nfa368abab1ac4443a50afd944ae7f95a |


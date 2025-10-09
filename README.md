# Sui-Move-Ontological-Framework

We introduces a comprehensive, multi-layered ontological framework designed for the formal modeling and security analysis of smart contracts written in the Sui Move language.

## Abstract

The proliferation of decentralized applications (dApps) has highlighted the critical need for robust security analysis of smart contracts. Business logic vulnerabilities, which stem from inconsistencies between a contract's intended design and its on-chain implementation, pose a significant threat that traditional code-level analysis tools often miss. This research presents a novel framework to address this gap by creating a semantic bridge between high-level architectural intent and low-level code implementation in the Sui Move ecosystem.

Our framework is composed of three integrated layers:

1. An OWL ontology that formally models the core components of the Sui Move language.
2. A curated library of four fundamental secure design patterns.
3. A set of Object-Centric Dynamic Condition Response (OC-DCR) graphs that specify the expected behavior of these patterns.

This repository provides the complete ontology, the DCR graph models, and other relevant materials.

## Repository Structure

- `/ontology/`: Contains the core OWL ontology file.
- `/images/`: Contains visual representations of the DCR graphs for the four security patterns discussed in the paper.
- `/codebases/`: Contains the codebases upon which the ontology was externally validated.

## The Ontology

The core of this research is the Sui Move ontology, which is provided in the `ontology` directory. It is structured into four interconnected layers:

- **Structural Layer**: Models the syntax and core components of the Sui Move language, derived from its formal grammar.
- **Architectural Layer**: Enriches the structural layer with concepts from the Sui architecture, such as the object model and ownership types.
- **Behavioral Layer**: Formally models the intended dynamic behavior of smart contracts using OC-DCR graphs.
- **Verification Layer**: Models components of the Move Prover to support the analysis of formal specifications.

## DCR Graph Models

The research formally models four critical secure design patterns using DCR graphs to represent their expected control flow and state dependencies. The visual models for these graphs are included in the `/images` directory.

1. **Access Control**: Ensures only authorized entities can execute specific functions.
2. **Circuit Breaker**: Provides a fail-safe mechanism to suspend critical functions in emergencies.
3. **Time Incentivization**: Uses temporal constraints to reward or penalize actions.
4. **Escapability**: Models stateful business logic to prevent unintended states.


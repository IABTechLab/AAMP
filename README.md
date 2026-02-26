# AAMP -- Agentic Advertising & Marketplace Protocol

### IAB Tech Lab Open Framework

AAMP (Agentic Advertising & Marketplace Protocol) is an open, modular
framework developed under IAB Tech Lab to enable interoperable Buyer,
Seller, Registry, and Direct orchestration agents within digital
advertising ecosystems.

This repository serves as the central hub for the AAMP ecosystem.

------------------------------------------------------------------------

# Executive Summary

AAMP defines a structured, interoperable approach for implementing
agent-based workflows across advertising participants.\
The framework separates responsibilities into clearly defined agent
roles to ensure transparency, scalability, and independent adoption.

Designed for: - Standards committees and industry working groups\
- Engineering teams implementing agent frameworks\
- PR and marketing stakeholders communicating innovation\
- Ecosystem participants evaluating adoption

------------------------------------------------------------------------

# Ecosystem Structure

## Core Hub

**AAMP (this repository)**\
- Architecture overview\
- Governance model\
- Ecosystem navigation\
- Cross-repository coordination

## Reference Implementations

### 1. Agentic Direct (Core Orchestration)

https://github.com/IABTechLab/agentic-direct\
Provides the core communication framework and orchestration layer for
agent interaction.

### 2. Buyer Agent

https://github.com/IABTechLab/buyer-agent\
Reference implementation of demand-side agent logic and decision
workflows.

### 3. Seller Agent

https://github.com/IABTechLab/seller-agent\
Reference implementation of supply-side coordination and marketplace
interaction.

### 4. Registry Agent (Example)

https://github.com/IABTechLab/registry-agent-example\
Demonstrates agent discovery, registration, and coordination patterns.

------------------------------------------------------------------------

# Architecture Overview

Buyer Agent\
↕\
Agentic Direct (Orchestration Layer)\
↕\
Seller Agent\
↕\
Registry Agent

Each component: - Operates independently\
- Maintains its own release cycle\
- Has dedicated issue tracking\
- Can be adopted standalone

------------------------------------------------------------------------

# Release & Versioning Model

AAMP follows a modular release strategy:

-   Each repository uses independent semantic versioning.
-   Releases are published via GitHub tags and release notes.
-   Cross-repository alignment occurs via governance coordination.
-   The AAMP Hub references stable releases for ecosystem clarity.

This avoids monorepo complexity while maintaining structured governance.

------------------------------------------------------------------------

# Governance & Contribution Model

-   Contributions should be submitted in the respective child
    repository.
-   Architectural proposals may be initiated in the AAMP Hub.
-   Cross-cutting protocol changes should be discussed before
    implementation.
-   All repositories follow IAB Tech Lab contribution and code of
    conduct policies.

------------------------------------------------------------------------

# Industry Benefits

-   Single PR & marketing entry point\
-   Clear separation of responsibilities\
-   Independent component adoption\
-   Scalable open-source governance\
-   Enterprise-aligned architecture\
-   Standards-ready ecosystem structure

------------------------------------------------------------------------

# Official Links

Organization: https://github.com/IABTechLab\
AAMP Hub: https://github.com/IABTechLab/AAMP

------------------------------------------------------------------------

AAMP is designed to foster collaborative innovation and interoperable
agent-based experimentation within digital advertising systems.

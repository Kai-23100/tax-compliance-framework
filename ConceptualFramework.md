# Conceptual Framework: Compliance Pathways for Revenue Mobilisation

This diagram represents the three pathways to tax compliance: **voluntary, enforced, and structural**.  
Structural compliance embeds tax obligations in transactional infrastructure, automatically triggering revenue mobilisation via Layer 1 transaction capture → Layer 2 rule engine → Layer 3 automated remittance, while Layer 4 governance ensures legitimacy and accountability.  
Independent variables for structural compliance are explicitly linked to the layers they influence.

```mermaid
graph TD

    %% =======================
    %% CORE PATHWAYS
    %% =======================

    VC["Voluntary Compliance\nTax morale\nInstitutional trust"]
    EC["Enforced Compliance\nAudits\nPenalties"]
    DA["Digital Economic Activity\nMobile money\nBanks\nDigital platforms"]

    %% =======================
    %% STRUCTURAL LAYERS
    %% =======================

    L1["Layer 1: Transaction Capture\nDigital systems capture\nTaxable events"]
    L2["Layer 2: Rule Engine\nApply tax rules\nRates and exemptions"]
    L3["Layer 3: Remittance\nAutomatic deduction\nTax payment"]
    G["Layer 4: Governance\nOversight\nAccountability\nLegitimacy"]

    %% =======================
    %% DEPENDENT VARIABLE
    %% =======================

    RM["Revenue Outcomes\nYield\nCoverage\nTimeliness"]

    %% =======================
    %% INDEPENDENT VARIABLES
    %% =======================

    IV1["IV1: Digital Coverage\nExtent of digital payments"]
    IV2["IV2: Rule Engine Quality\nAccuracy of tax rules"]
    IV3["IV3: Institutional Capacity\nURA capability"]
    IV4["IV4: Political Economy\nSupport vs resistance"]

    %% =======================
    %% FLOWS
    %% =======================

    VC --> RM
    EC --> RM

    DA --> L1
    L1 --> L2
    L2 --> L3
    L3 --> RM
    G --> RM

    %% =======================
    %% IV LINKS
    %% =======================

    IV1 --> L1
    IV2 --> L2
    IV3 --> G
    IV4 --> G

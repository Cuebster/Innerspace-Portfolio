# INNERSPACE
## Proprietary Modular Software Infrastructure

**Independent software products. Explicit SDK and adapter boundaries. One integrated infrastructure suite.**

Innerspace is an integrated infrastructure suite assembled from independently developed software products.

Its architecture uses product-owned capabilities, SDKs, adapters, endpoints and explicit integration contracts. Products retain their separate identities, responsibilities and authority boundaries.

**This repository is a presentation portfolio only. It does not distribute software or grant an open-source or commercial license.**

### Portfolio navigation

- [Engineering Evidence — Accepted Checkpoints and Integrity References](ENGINEERING_EVIDENCE.md)
- [Licensing, Rights, and Controlled Access](LICENSING_AND_ACCESS.md)
- [Potential Real-World Robotics Applications — Concept, Not Deployment](ROBOTICS_APPLICATION_CONCEPT.md)

## Technology Portfolio

| Product | Engineering Domain |
| --- | --- |
| **KZip** | Durable infrastructure, archive/node operations and native interfaces |
| **KyleDaemon** | Memory infrastructure and signed task/worker coordination |
| **KyleDaemon Audio (KDA)** | Native audio endpoint, SDK and integration adapters |
| **KyleDaemon LLM** | Memory client/workbench, source selection and endpoint integration |
| **Vivian** | Spatial reference infrastructure, mapping and coordinate-aware SDK |
| **KyleDaemon MVP** | Original source baseline and reference foundation |
| **In Utero** | Full-stack reference application demonstrating interoperability |

## Visual technology architecture

```mermaid
flowchart TB
    subgraph Products["INDEPENDENT PRODUCT SURFACES"]
        direction LR
        KZ["KZip"]
        KD["KyleDaemon"]
        AU["KDA Audio"]
        LM["KyleDaemon LLM"]
        VI["Vivian Spatial"]
    end
    BASE["KyleDaemon MVP<br/>source baseline"] -. "heritage" .-> KD
    KZ --> API["Product SDKs, endpoints & explicit contracts"]
    KD --> API
    AU --> API
    LM --> API
    VI --> API
    API --> AD["Application-owned adapters & authority"]
    AD --> REF["In Utero<br/>full-stack reference application"]
    AD -. "possible licensed integrations" .-> OTH["Other domains<br/>(not claimed as delivered)"]
```

This is an **integration overview**, not a runtime dependency diagram. Each product remains independently owned, and In Utero is an application consuming the stack—not the stack itself. [Explore the visual architecture and product boundaries](ARCHITECTURE_OVERVIEW.md).

## How the products fit together

Independent providers expose capabilities through their own endpoints and SDK contracts. Adapters connect these capabilities to a consumer application without transferring product ownership or application authority.

**In Utero** is a UE/Cesium-based reference implementation demonstrating interoperability. It is not the reason the independent infrastructure products exist, and its game-domain acceptance does not authorize physical-world operations.

## Candidate real-world applications

A supervised **robotics-assisted moving and materials-handling service** is one potential application for independently licensed Innerspace components. This is a future integration concept, **not an accepted physical robot deployment or workplace safety claim**. Real hardware requires separate sensing, control, protective systems, risk assessment and field validation. See the [robotics application concept](ROBOTICS_APPLICATION_CONCEPT.md).

## Engineering demonstration

Build220 and Build221 established documented integration, packaging, and reconciliation checkpoints. KZip and KyleDaemon Audio have accepted standalone native packages; other published product repositories may represent source/interfaces that still depend on the accepted master distribution for complete offline runtime reconstruction.

See the [engineering evidence overview](ENGINEERING_EVIDENCE.md) for the accepted scope and integrity references. The underlying verification receipts are retained privately and have not been presented here for independent public inspection.

## Commercial positioning and availability

Innerspace is presented as proprietary technology intended for **controlled commercial licensing and authorized technical evaluation**. Publication of a product description, screenshot, or engineering summary is not permission to use, reproduce, deploy, or redistribute the underlying software.

An approved business inquiry channel and evaluation terms will be provided separately; **no public access to implementations or trial endpoints is offered through this repository**.

Individual capability descriptions and acceptance records are not claims of universal production readiness, industrial certification, or security certification. Rights and access are described in [Licensing and Access](LICENSING_AND_ACCESS.md).

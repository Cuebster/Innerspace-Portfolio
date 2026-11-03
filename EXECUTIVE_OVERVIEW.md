# INNERSPACE — Executive Technology Overview

**Proprietary modular software infrastructure | Private corporate portfolio | November 2026**

## Executive summary

**Innerspace** is a modular software infrastructure suite developed around independently owned products, explicit software development kits (SDKs), service endpoints, and adapter contracts. The engineering objective is to compose capabilities across applications without making any single application the owner of the underlying infrastructure or transferring its decision-making authority.

The portfolio covers data and artifact infrastructure, memory and worker coordination, audio services, source-selected AI client functions, and spatial-reference services. **In Utero**, a Mars-themed Unreal Engine/Cesium simulation and game, is an integrated reference application demonstrating use of those components. It is **not** the infrastructure suite itself.

This is a presentation of existing products, internally accepted engineering checkpoints, and possible licensed integration opportunities. It is not an offer of source code, a public download, or a claim of universal production certification.

## Technology portfolio

| Product | Core responsibility | Integration relevance |
| --- | --- | --- |
| **KZip** | Durable archive/node infrastructure, native interfaces and SDK contracts | Application-owned artifact and infrastructure workflows |
| **KyleDaemon** | Memory endpoint and bounded, signed task/worker coordination | Context retrieval, delegated work and result reconciliation |
| **KyleDaemon Audio (KDA)** | Native audio endpoint, SDK and adapters | Audio handling through independently managed services |
| **KyleDaemon LLM** | Source-selected memory client/workbench and selected export | Controlled context selection and operator-facing tools |
| **Vivian** | Spatial-reference SDK and endpoint, frame/unit-aware context | Coordinate and mapping support without claiming control of the consumer |
| **KyleDaemon MVP** | Preserved original source baseline | Product heritage and reproducible source identity; not a separate newly accepted runtime |
| **In Utero** | Unreal Engine/Cesium multiplayer game and simulation | Reference consumer demonstrating product integration in a simulated world |

## Why the architecture matters

**Clear boundaries.** Products retain their own interfaces, states, dependencies, and histories. The consuming application remains responsible for authorizing actions and committing authoritative state.

**Selective integration.** A customer or integrator would evaluate the particular endpoints, SDKs and adapters relevant to their application. The architecture does not require every product in every deployment.

**Traceable engineering.** The portfolio differentiates source publication, accepted standalone packages, a frozen combined runtime, and features under ongoing development instead of treating them as interchangeable.

## Demonstrated engineering position

Build220 documented selected full-stack integration. Build221 R1 established an internally accepted frozen master with retained verification evidence. **KZip** and **KyleDaemon Audio** have accepted standalone native packages. Other product repositories may contain source and interfaces without all dependencies required to reconstruct the accepted offline runtime independently.

In Utero demonstrates integration in the game/simulation domain. New gameplay and robotics-simulation work should be evaluated against its own test evidence; those demonstrations do **not** establish that any physical robot is deployed, certified, or safe to operate.

Detailed scope and retained receipt hashes are in [Engineering Evidence](ENGINEERING_EVIDENCE.md). The integration diagram and ownership rules are in [Architecture Overview](ARCHITECTURE_OVERVIEW.md).

## Potential commercial evaluation paths

- **Software integrators:** evaluate selected infrastructure products, interfaces, SDKs and adapters under a defined application-owned authorization model.
- **Simulation and interactive systems:** evaluate the game-domain reference integration and product boundaries demonstrated through In Utero.
- **Robotics research and material-handling concepts:** evaluate whether selected components could support a separately designed, supervised physical system. This is a **candidate application**, not a delivered physical robot, commercial moving service, or validated safety system. See [Robotics Application Concept](ROBOTICS_APPLICATION_CONCEPT.md).

A practical next step for an interested party is a scoped discussion with the rights holder, followed by separately approved technical review, confidentiality/access terms where appropriate, and a written license or evaluation agreement. **No pricing, trial access, deployment timetable, or distribution entitlement is offered by this portfolio.**

## Existing development media

- [Owner-maintained Facebook development videos and screenshots](https://www.facebook.com/KyleDanielWebster) — external source archive; individual posts may require Facebook access.
- [In Utero theme-music playlist on YouTube Music](https://music.youtube.com/playlist?list=PLW6M-9Tq8S70) — creator-maintained music presentation; this link does not imply that all tracks are integrated into the live game.

These are links to existing external material, **not** copies or independently audited demonstrations. Their availability and contents are controlled by the external platforms and owner.

## Rights and access

The source, binaries, internal configurations, model assets, datasets, full receipt archives and implementation details are **not distributed** through this corporate portfolio. Any commercial, SDK, source or evaluation access requires separate rights-holder authorization and written terms; see [Licensing and Access](LICENSING_AND_ACCESS.md).

[Return to Innerspace Portfolio](README.md).

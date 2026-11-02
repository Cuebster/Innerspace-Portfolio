# INNERSPACE — Potential Real-World Robotics Applications

**Concept and evaluation roadmap · Not an accepted physical-robot deployment · Proprietary portfolio**

Innerspace has been developed around independent software infrastructure, SDKs, adapters, endpoint contracts, and caller-owned authority. **Physical robotics is a potential application domain** for that architecture. In Utero demonstrates integration in a simulated environment; it is not evidence that any physical robot has already been certified, deployed, or proven safe in a workplace.

The design intent is to support useful, supervised work systems with bounded tasks, clear accountability, and explicit safety controls. This is a commercial *candidate*, not an available robotic moving service or a statement of demonstrated physical-world capability.

## Example application: robotics-assisted moving and material handling

Consider a moving operation: relocating packed boxes and other eligible objects from a designated pickup area to a truck loading area, warehouse bay, or marked drop-off station. A robotic worker could eventually assist with repeatable transport steps if the necessary physical equipment, perception, controls, validation, and operating procedures were independently developed and accepted.

**Proposed task sequence (not a demonstrated deployment):**

1. A supervisor defines the authorized work zone and approved objects, routes, payload limits, and stop conditions.
2. A robot hardware and application controller establishes its **live sensor state** and validated localization in the work zone.
3. The application requests suitable planning, spatial context, task coordination, or audio capabilities from independent Innerspace product endpoints as needed.
4. The **robot application's own safety-rated controls and authorized motion system** decide whether any requested action can proceed; language-model or recalled context does not directly actuate hardware.
5. The robot performs only a bounded, supervised movement; the application records observed execution and completion or failure evidence.
6. Obstruction, loss of localization, load instability, human proximity, communication failure, or an emergency stop cause a defined protective response instead of an improvised continuation.

Start with a controlled, flat-floor materials-handling scenario; household moving, stairs, uncertain loads, narrow passages, heavy furniture, and close human interaction are **outside the initial proposed pilot**.

## How existing product roles could support a future robotics adapter

| Product | Potential role in a robot-integrator application | Boundary |
| --- | --- | --- |
| **KyleDaemon** | Task coordination, bounded worker requests, memory and correlated results. | No direct permission to energize motors or override a robot safety controller. |
| **Vivian** | Spatial/reference context, frames, units, and relative positions. | Real robot localization, live sensor validation, and collision avoidance must be separately developed and verified. |
| **KZip** | Integrity-oriented infrastructure, reference endpoints, durable artifact handling. | Not a replacement for safety-certified motion control or protective stop mechanisms. |
| **KyleDaemon Audio (KDA)** | Audio status, prompts, or alerts via an application adapter. | A voice or audio event is never itself a motion authorization. |
| **KyleDaemon LLM** | Selected-source context, operator workbench, and explainable task-assistance surface. | Suggestions require current-state validation and explicit authorization before execution. |
| **KyleDaemon MVP** | Original preserved source foundation. | Not an independently deployed robotics runtime claim. |
| **In Utero** | Existing simulation/reference consumer demonstrating product interoperability. | Game-domain verification does not establish physical-world performance or robot safety. |

Not every future robotic system would need every product. The application and hardware owner decide which components to integrate, under separate authorization.

## Required work before claiming physical-world readiness

A proposed integration requires **new engineering and evidence**, including:

- A named hardware platform and its independent sensors, drive, lifting/manipulation systems, load ratings, and controller architecture.
- An explicit physical-world adapter, hardware-ownership model, permission model, and bounded command/response contract.
- Verified robot-centered localization, environmental perception, obstacle detection, human-presence handling, and payload stability.
- Protective stops, emergency stop systems, independent safety interlocks, speed/force limits, safe startup/shutdown, and fail-safe behavior appropriate to the actual hardware.
- Separation between non-safety intelligence and the independent controls responsible for keeping people and property safe.
- Offline simulation, hardware-in-the-loop testing, controlled-area testing, then supervised on-site trials with documented acceptance criteria and risk assessment.
- Security, maintenance, operator training, liability, applicable requirements and independent review appropriate to the chosen environment.

**No industrial safety certification, autonomous workplace safety, lifting capability, or real-world robot deployment is claimed by this document.**

## Commercial direction

Potential licensees could evaluate selected Innerspace endpoints and SDK adapters under negotiated terms, using their own robot control systems and safety infrastructure. This portfolio contains no production hardware configuration, actuator commands, proprietary source, SDK implementations, or field deployment instructions.

See [Architecture Overview](ARCHITECTURE_OVERVIEW.md), [Engineering Evidence](ENGINEERING_EVIDENCE.md), and [Licensing and Access](LICENSING_AND_ACCESS.md). For what demonstrations may be shown publicly, see [Demonstration Evidence Plan](DEMONSTRATION_EVIDENCE_PLAN.md).

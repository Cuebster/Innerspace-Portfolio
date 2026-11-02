# INNERSPACE — Engineering Evidence and Verification

**Public-disclosure candidate | Proprietary software | Documentation only**

This page describes *specific internally accepted engineering checkpoints* for the Innerspace software infrastructure. The underlying products, runtime artifacts, detailed receipts, SDK implementations, and engineering records are not publicly distributed. The checkpoints are not claims of independent third-party certification.

## Accepted engineering scope

| Checkpoint | What was established | Important boundary |
| --- | --- | --- |
| **Build220** | Selected whole-stack integration demonstration connecting independent product endpoints and application adapters. | Demonstrated integration does not imply every deployment scenario has been tested. |
| **Build221 R1** | Accepted and frozen whole-stack master with retained source, runtime reconstruction, and verification evidence. | A frozen accepted package is not an unrestricted commercial release. |
| **KZip** | Accepted standalone native infrastructure package, with CLI/reference interfaces and SDK contracts. | Applications must still authorize and integrate their own operations. |
| **KyleDaemon Audio (KDA)** | Accepted independent native audio endpoint, SDK, and bridge-adapter package. | No general real-time performance or production certification is implied. |
| **Shared SDK/adapter contracts** | Accepted integration contracts for capability composition, workers, client adapters, server responsibilities, and endpoint mapping. | The contracts do not transfer ownership, execution authority, or application state authority. |
| **Product/source reconciliation** | Verified independent product/source histories and declared source identities against the accepted Build221 publication; KZip and Audio standalone roots reconciled separately. | Source mirrors do not necessarily contain a self-sufficient runtime distribution. |
| **In Utero reference application** | Game-domain integration demonstrated with independently owned Innerspace interfaces in a UE/Cesium environment. | The game is a reference consumer, not the definition of the infrastructure. |

These descriptions reflect the accepted Build220/Build221 documentation and retained records. Ongoing development and separately demonstrated features have their own acceptance scope.

## Integrity references — retained private acceptance receipts

The following SHA-256 values identify accepted receipt files documented in the Build221 stack guide. They are **integrity anchors**, not downloadable artifacts, security certifications, or proof of independent review. An authorized reviewer would need access to the corresponding exact receipt bytes to reproduce the hash comparison.

| Receipt category | SHA-256 |
| --- | --- |
| Build221 final acceptance/freeze | `78d95af932d7c3bd27464d547f1225bd88f25569b56bc489ea0d17a4ee4c9010` |
| Product/game source and documentation reconciliation | `03dc7317946efb12187d87a10a74778ed5c1214158261ef6080afce03209b798` |
| KZip and Audio standalone package/root reconciliation | `f02e80a376f5b4c03ede97731973f93b6b110ee055c8276e5d7bc284664257b9` |
| Audio historical layout reconciliation | `94c7e17be1701abfc798ccdab5dd1fc11243f2adcde2d626db1edeed88228c04` |

## Disclosure and evaluation boundary

**Public information:** high-level product roles, integration relationships, scope-qualified checkpoint descriptions, and these receipt fingerprints.

**Not offered publicly:** source code, SDK implementations, native binaries, model files, private datasets, service credentials, internal interfaces/protocol details, full logs, internal evidence archives, or unrestricted runtime endpoints.

Any deeper technical examination requires a separately authorized evaluation scope and appropriate agreements. A publication of descriptive documentation does **not** grant a software license.

No public claim is made here of industrial certification, physical-world operational authorization, comprehensive security assessment, universal performance fitness, or completed production deployment.

For product positioning see [Portfolio Overview](README.md). For access policy see [Licensing and Access](LICENSING_AND_ACCESS.md).

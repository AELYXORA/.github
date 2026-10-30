# AELYXORA

### Imagine. Design. Engineer.

**Architecture-first. AI-driven. Built for systems and hardware.**

AELYXORA is an open-source initiative developing **AELYXORA Studio**: an AI-native engineering environment where the primary workspace is an interactive **Project Architecture Map** with contextual AI chat.

Instead of starting from source files or forms, engineers design systems as connected components, interfaces, devices and contracts. **Humans own the architecture; AI primarily implements and tests components within its boundaries.**

## What makes AELYXORA different?

- **Architecture Map at the center** — mind-map clarity with typed, UML-inspired relationships, dependencies and data flows.
- **Context-aware AI engineering** — select a component or subgraph, inspect the exact shared context, request an implementation and review changes before applying them.
- **Hardware-aware software development** — CPU/ISA, ABI, memory, buses, peripherals, drivers, interrupts, DMA and protocols are first-class architectural concerns where applicable.
- **Assembly-first implementation** — native components and an in-house declarative UI runtime, with per-target architecture/OS adaptations and LLVM/Clang tooling.
- **Human control and verifiable results** — explicit contracts, source ownership, local tests and evidence attached to the architecture.

## Intended workflow

1. **Design** a project as a typed architecture graph.
2. **Define** component responsibilities, interfaces and target hardware constraints.
3. **Ask AI** to implement a selected component without silently rewriting the architecture.
4. **Review** proposed graph/source changes, approve them, build and test locally.
5. **Inspect** results, source and diagnostics from the corresponding map nodes.

## AELYXORA Studio

[Explore the project, architecture and roadmap](https://github.com/AELYXORA/Studio).

The Studio targets low-level and hardware-oriented software: native applications, libraries, drivers, firmware-facing tools, embedded interfaces and protocol implementations.

Our direction is an **in-house declarative UI and Assembly-first core**, not Qt/QML, C++ or Delphi FMX. Cross-platform contracts are shared, but native Assembly implementations must be verified separately for each CPU/ABI.

**AI account integration is a goal, not an available feature.** We want an officially supported ChatGPT sign-in experience where eligible, without credential scraping or treating a Plus subscription as a general-purpose API key.

## Status

**Early experimental foundation.** The repository currently contains a minimal Linux x86-64 Assembly UI-tree validator and local test harness. There is no released IDE, interactive architecture canvas, renderer or connected AI chat yet.

Development is local-test-driven; GitHub Actions/CI remains disabled until release preparation.

---

**AELYXORA — Imagine. Design. Engineer.**

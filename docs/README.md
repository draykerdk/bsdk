> A structure for composing and revising the Dk kernel.

BSDK studies how functions, modules and their relationships can form a coherent base for Dk. Its central question is how a system can evolve while the parts built on it remain understandable.

The proposed base structure makes functional relationships part of the model, supporting explicit interfaces, dependency analysis and revision.

A useful foundation gives future contributors a way to examine and improve the system beyond the choices of its first authors.

## A practical example

A revised module should make it possible to identify which dependent functions need review before the change is adopted. This is an illustration of the proposed design.

## Why this exists

BSDK is the base structure the intelligence grows from — the part that decides what the rest can become.

The argument in full is on the [manifesto](https://drayker.org/manifesto/); the [economy page](https://drayker.org/economy/) states plainly what contributing here earns and what it does not.

## What is published here

Motions for resolution. Not a specification.

All proposed resolutions presented here are solutions to the requirements of Dk and the Drayker platform, and **only those requirements are final**. The motions illustrate what should be done; the definitive architecture is expected to be structured around optimal solutions proposed and developed with metaprogramming intelligent algorithms and research organized through [DFMP](https://dfmp.drayker.org) and other methods.

That distinction is the point of this repository, not a disclaimer on it. A structure decreed once is a structure that cannot learn.

## How it fits the whole

BSDK is the structural layer [Dk](https://dk.drayker.org) stands on: the DNA-like base structure the kernel is assembled from, and the part that decides what the rest can become. It also holds the base layer of the constitution: the rules that keep the parts coordinated and the system coherent, many of them grounded in the E.C.H. triad of Expansion, Complexity and Harmony, and the mandate of the global Dk, its duties and fundamental commitments to members. That base is simple and much harder to change than anything else, and a change to the members' constitution must be compatible with it, or the global Dk blocks the change until the kernel itself changes.

BSDK is to the network what genes are to an organism: the inheritance of the network can change too, but only by the hardest path the constitution provides. A change to the core requires the explicit agreement of at least nine out of every ten active Dzwecks, given in two rounds, with the new core running in parallel with the current one between them; the rule is set out in [GOVERNANCE §3.5](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md#35-what-only-members-decide). The global Dk builds the project with the Dzwecks and approves it or presents an alternative, but does not ratify; because every node belongs to a member and can refuse the update, adoption by the nodes is the final ratification. No change to the core happens in a single decision or in the heat of a crisis.

Everything above it leans on what this structure decides. [DFM](https://dfmp.drayker.org) gives it the shared vocabulary — the same language of functions and modules the method cuts work into is the language this base structure is proposed in. That shared language is also what lets DFM coordinate the layered, heterogeneous computing of the [Dk Network](https://dknetwork.drayker.org), with each machine doing the work it does best. [Dk](https://dk.drayker.org) is assembled from the structure — the intelligence cores, from the mini core of the personal Dk to the full core of the global Dk, are composed out of the pieces BSDK defines; [OSDK](https://osdk.drayker.org) and [UID](https://uid.drayker.org) are consumed through it; and because the structure is meant to evolve without discarding what still works, the whole ecosystem inherits that property. A structure decreed once is a structure that cannot learn — BSDK exists to be the opposite of that.

## The first motions

These come from the founding design notes. They are motions, written to be argued with and improved, not a specification.

**Functions.** Each function performs one minimal task and is structured like a document: it can be understood at a high level while keeping its low-level properties and performance. Functions are grouped into modules through structures such as decision trees. The structure is designed for distributed computing, so each function can run in a different place, in a different way.

**Modules.** Modules integrate functions in a fractal architecture: modules order other modules, which order functions. A block can hold information (data) or functions (processes). Abstraction modules handle information, and processing and optimization modules handle functions. The module's data structure guarantees redundancy for errors, so that Dk can detect and correct them.

**Fundamental modules.** The fundamental modules are basic functions followed by local and global resources across the network: small rules that create the emergent behaviour of many parts and support every module above them. BSDK orders functions in different ways through cellular automata governed by different rules.

**Immutability and clones.** All functions and modules are immutable. A change overwrites nothing: it is a mutant clone that runs in parallel with the original while both are still in use. Every function is converted into an optimized binary linked by hash to its original code. When Dk evolves a binary, the modification breaks the hash. It is then linked to the old function and documented in the oracle, [Dknowledge](https://dknowledge.drayker.org), until the network fully accepts it and it becomes the standard.

**Forgetting.** Once the new version is the standard, the old function is forgotten over time. A function or module that goes unused for a long time, such as one already optimized and replaced, becomes a fragment: a simplification of the original that takes a fraction of its former memory and can only be restored through reverse engineering and computational effort. The same holds for memory modules.

**Function types.** Functions carry specific data types and structure types. Computational modules define them, and evolutionary, AutoML and integration modules can create new ones, either to optimize heavily used functions and structures or to enable new functions, architectures and modules. One example is the parallel function, which uses several versions of itself with small changes and can serve as a whole layer of a neural network.

**AutoML and evolution.** AutoML modules can combine thousands of functions from the network, compare them, abstract them and create new modules to solve a problem or optimize an existing module. Evolutionary modules can create different functions and modules to meet needs or adapt to new environments. Categorization and addressing modules form fractal trees of functions, grouped by kinship, similarity, metadata and hyperparameters. These trees help nodes find functions and modules on the network and are vital to AutoML and evolution. The more modules share a function, the faster it becomes, because more nodes use, relay and process it, and the more the evolution layer keeps optimizing it.

**Dimensional primitives.** The base structure works with dimensional primitives: combinations formed from two or more base dimensions, 0 and 1, so that it can run on environments with different logics and circuits by adding or removing layers of dimensional abstraction, from conventional processors to quantum computers and other special-purpose chips. It is meant to let any hardware be used by the network: the structure recognizes the device, downloads the modules optimized for it and brings its computing resources to the network in a verifiable way.

**Verification and trust.** Every part built on the base structure is meant to be individually verifiable and provable, aiming at full coverage by tests and formal verification, from the low level to the high level. Confidence is held in degrees: it changes with the amount of evidence gathered and with the confidence of that evidence itself, forming a chain of trust. A function verified formally holds the highest degree and still needs support for the cases the verification does not cover. Confidence is also per use: a function trusted for the task it solves starts again for a different use, which grows as a parallel branch with its own chain of trust.

## The equation and the research behind it

The definitive form of BSDK is the **super equation**: the base structure that compresses the behavior of the network and the Dk. The research suggests its predictive modeling may be beyond human capacity alone — which is why the work is expected to be carried out by [Meta DFM](https://metadfmp.drayker.org), the evolutionary research and development super-agent. The equation is open research; the agent that will help find it is part of the same design.

The equation is itself evolutionary. The complexity that functions and modules generate feeds consensual optimizations back to the kernel function, producing an evolved equation that runs in parallel with the previous one and becomes dominant as it proves itself. It remains the most rigid function in the system, because it has to stay compatible with everything built on it. This is the technical side of the rule for the core set out above: the core changes only through a new version running beside the current one and adopted by the nodes.

## Where it stands on the path

Today BSDK is research in public: the motions above. It belongs to the substrate of Dk 0.1, whose exit condition is that the substrate moves from argument to testable specification ([Direction](https://dknowledge.drayker.org/roadmap/DIRECTION)). The base structure has to be refined and discussed before it enters production for version 0.1. Candidates for the equation are meant to be formulated in parallel projects and put through mathematical proofs, simulations, and security and complexity tests; the selection comes from rounds of testing and review, each candidate run through a DFM implementation specified for test cases. With the base specification in beta, the network and distributed-computing modules can be built on it, laying the bases of [Dk Network](https://dknetwork.drayker.org) and [OSDK](https://osdk.drayker.org). The final structure is ready only when there is verifiable evidence that it is among the best possible solutions, and even then the network can improve it through the rule for changing the core described above.

## State of this documentation

Still thin. The first motions, on functions, modules, fundamental modules, immutability, forgetting, AutoML, dimensional primitives and verification, are published above, with how the equation evolves and where BSDK stands on the path. Formal definitions, worked examples and the base protocol are not. If you are looking for a place where careful architectural writing would immediately matter, it is here.

## Contributing

Open an issue with the motion you want to argue for — that is how a resolution enters the process. Issues small enough for one person to finish carry the `open-function` label and appear on the board at [drayker.org](https://drayker.org/fn/).

Related: [`dk`](https://dk.drayker.org) · [`dk-network`](https://dknetwork.drayker.org) · [`dfmp`](https://dfmp.drayker.org)

English is the canonical language of this documentation; read other languages through automatic translation. Native translation and localization are planned for the Drayker sites.

---

Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Drayker belongs to its members, with no shareholders and no profit distribution, and its work is primarily voluntary. DAF is an autonomous federation of autonomous units, a basic and primitive form of PAP, implemented now. Current founding governance is documented in [`draykerdk/.github`](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md).

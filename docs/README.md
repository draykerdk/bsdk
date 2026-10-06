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

BSDK is the structural layer [Dk](https://dk.drayker.org) stands on: the DNA-like base structure the kernel is assembled from, and the part that decides what the rest can become. It also holds the base layer of the constitution: the rules that keep the parts coordinated and the mandate of Dk Global. That base is much harder to change than anything else, and a change to the members' constitution must be compatible with it, or Dk Global blocks the change until the kernel itself changes.

Everything above it leans on what this structure decides. [DFM](https://dfmp.drayker.org) gives it the shared vocabulary — the same language of functions and modules the method cuts work into is the language this base structure is proposed in. [Dk](https://dk.drayker.org) is assembled from it — the intelligence cores, from the mini core of Dk Personal to the full core of Dk Global, are composed out of the pieces BSDK defines; [OSDK](https://osdk.drayker.org) and [UID](https://uid.drayker.org) are consumed through it; and because the structure is meant to evolve without discarding what still works, the whole ecosystem inherits that property. A structure decreed once is a structure that cannot learn — BSDK exists to be the opposite of that.

## The first motions

These come from the founding design notes. They are motions, written to be argued with and improved, not a specification.

**Functions.** Each function performs one minimal task and is structured like a document: it can be understood at a high level while keeping its low-level properties and performance. Functions are grouped into modules through structures such as decision trees. The structure is designed for distributed computing, so each function can run in a different place, in a different way.

**Modules.** Modules integrate functions in a fractal architecture: modules order other modules, which order functions. A block can hold information (data) or functions (processes). Abstraction modules handle information, and processing and optimization modules handle functions. The module's data structure guarantees redundancy for errors, so that Dk can detect and correct them.

**Immutability and clones.** All functions and modules are immutable. A change overwrites nothing: it is a mutant clone that runs in parallel with the original while both are still in use. Every function is converted into an optimized binary linked by hash to its original code. When Dk evolves a binary, the modification breaks the hash. It is then linked to the old function and documented in the oracle, [Dknowledge](https://dknowledge.drayker.org), until the network fully accepts it and it becomes the standard.

**Forgetting.** Once the new version is the standard, the old function is forgotten over time. A function or module that goes unused for a long time, such as one already optimized and replaced, becomes a fragment: a simplification of the original that takes a fraction of its former memory and can only be restored through reverse engineering and computational effort. The same holds for memory modules.

**Function types.** Functions carry specific data types and structure types. Computational modules define them, and evolutionary, AutoML and integration modules can create new ones, either to optimize heavily used functions and structures or to enable new functions, architectures and modules. One example is the parallel function, which uses several versions of itself with small changes and can serve as a whole layer of a neural network.

**AutoML and evolution.** AutoML modules can combine thousands of functions from the network, compare them, abstract them and create new modules to solve a problem or optimize an existing module. Evolutionary modules can create different functions and modules to meet needs or adapt to new environments. Categorization and addressing modules form fractal trees of functions, grouped by kinship, similarity, metadata and hyperparameters. These trees help nodes find functions and modules on the network and are vital to AutoML and evolution. The more modules share a function, the faster it becomes, because more nodes use, relay and process it, and the more the evolution layer keeps optimizing it.

## The equation and the research behind it

The definitive form of BSDK is the **super equation**: the base structure that compresses the behavior of the network and the Dk. The research suggests its predictive modeling may be beyond human capacity alone — which is why the work is expected to be carried out by [Meta DFM](https://metadfmp.drayker.org), the evolutionary research and development super-agent. The equation is open research; the agent that will help find it is part of the same design.

## State of this documentation

Still thin. The first motions, on functions, modules, immutability, forgetting and AutoML, are published above. Formal definitions, worked examples and the base protocol are not. If you are looking for a place where careful architectural writing would immediately matter, it is here.

## Contributing

Open an issue with the motion you want to argue for — that is how a resolution enters the process. Issues small enough for one person to finish carry the `open-function` label and appear on the board at [drayker.org](https://drayker.org/fn/).

Related: [`dk`](https://dk.drayker.org) · [`dk-network`](https://dknetwork.drayker.org) · [`dfmp`](https://dfmp.drayker.org)

English is the canonical language of this documentation; read other languages through automatic translation. Native translation and localization are planned for the Drayker sites.

---

Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Drayker is non-profit, and its work is primarily voluntary. DAF is proposed governance architecture; current founding governance is documented in [`draykerdk/.github`](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md).

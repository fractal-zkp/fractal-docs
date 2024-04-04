# Overview

Fractal is a modular blockchain network composed of the following layers:

* [fractal-hub-availability-and-finality-layer.md](fractal-hub-availability-and-finality-layer.md "mention") - Responsible for providing fast finality and data availability.
* [unity-validity-sequencer-layer.md](unity-validity-sequencer-layer.md "mention") - Responsible for sequencing / executing (cross-rollups) transactions and building rollup blocks.
* [prover-layer.md](prover-layer.md "mention") - Responsible for generating proofs for rollups.
* [orchestration-layer.md](orchestration-layer.md "mention") - Responsible for assigning sequencers and provers to rollups.
* [aggregation-layer.md](aggregation-layer.md "mention") - Responsible for aggregating proofs from rollups and facilitating safety for cross-rollup messaging.

These modular layers combine to provide a comprehensive platform for effortless deployment of decentralized zero-knowledge rollups. Please see the respective pages linked above to learn more about each layer.&#x20;

<figure><img src="../.gitbook/assets/fractal-architecture (1).png" alt=""><figcaption></figcaption></figure>

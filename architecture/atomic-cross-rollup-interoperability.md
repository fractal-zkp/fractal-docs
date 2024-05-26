# Atomic Cross-Rollup Interoperability

To enable atomic cross-rollup transactions, our architecture employs a novel concept known as the "Super Block Builder Paradigm." Within this framework, we introduce a pivotal component: the Super Builder, also depicted to as Sequencer D in the diagram below. This Super Builder operates full nodes for every rollup within our platform, granting it comprehensive access to the complete state of these rollups.

Given the impracticality of expecting a single block producer to construct full blocks for every rollup, we also incorporate the role of the Native Builder. Within a given time slot, both a Native Builder and the Super Builder generate blocks for each rollup. The Native Builders are responsible for producing blocks that include transactions native to their respective chains. These can be straightforward, intra-chain transactions or asynchronous cross-chain transactions. Conversely, the Super Builder specializes in creating blocks that contain atomic cross-chain transactions.

The block produced by the Super Builder acts as a "Super Block," effectively aggregating a block for each rollup involved in the cross-rollup transactions it processes. This approach results in the production of two distinct types of blocks for each rollup in every slot: one from the Native Builder and one Super Block from the Super Builder. The Super Block is pivotal for facilitating atomic transactions across rollups, ensuring consistency and atomicity in a decentralized and distributed environment.

This dual-block mechanism ensures that transactions within the same rollup can proceed efficiently and independently, while cross-rollup transactions are handled securely and atomically by the Super Builder. The introduction of this paradigm marks a significant advancement in blockchain technology, offering a robust solution for seamless, secure, and efficient cross-rollup transactions.

<figure><img src="../.gitbook/assets/multi-block.drawio (1) (1).png" alt=""><figcaption></figcaption></figure>

# Knowledge Map for JAM
## About Join-Accumulate Machine
```mermaid
mindmap
  id)Join-Accumulate Machine(
    Non-upgradable
      Fixed Parameters
    Networking
      QUIC Protocol
        Direct Point-to-Point Connections
      No Gossiping
      Grid Diffusal
    Efficient Block Production
      SAFROLE
        SASSAFRAS simplication
        Minimally opinionated as possible
        SNARK-based block production algorithm
    Efficient Block Processing
      Pipelining 
    Domain-specific Chain
      Rollup Reactor
        High Resilient Data Availability
        Rollup Hosting
    Smart Contract Similarity
      Token Hosting
      Permissionless Code Execution
      State Encapsulation & Partition
        Service
          I/O
            Work Package (Input)
              Work Item
              Core Assignment
            Work Report (Output)
              Work Result
          Parachain as a Service
          Permissionless Creation
          Entry Points
            Refine
            Accumulate
            OnTransfer
    Polkadot Virtual Machine
      RISC-V ISA
      Deterministic
      Consensus-sensitive
      Friendly to metering
      Lacks complexity and excessive opinionation
    Backward Compability
      Polkadot SDK
      Agile Coretime
    Full XCMP Support
    Transactionless
      Metering
      No transaction distribution/pool
      Extrinsic
        Security Framework
          Guarantees
          Assurances
          Judgments
        Preimages
        Tickets
    Polkadot
      Capability
        Agile Coretime
        Parachain
      Distributed Data Availability
        Parachain Core
      Auditing and guarantees system for computation
        Shared Security
```
## Polkadot
- Scalable, heterogenous, sharded, multi-chain network
- Permissionless and ubiquitous computer
- Decentralized open-source community
- Digital-native sovereign network
### BREAKDOWN of Polkadot
Link to visualization: https://excalidraw.com/
### Decision of Polkadot
- Decisions that can be easily changed in the future.
- Features can be included into the protocol at later time
- Changes can be considered as part of the evolution of the protocol
- Type 1 decisions of Polkadot:
  - XCMP is the core design of Polkadot. Bridges in the blockchain world is insecure and having a transport protocol lyings in the core of the protocol to power shardeds of the network.
  - Any consumer hardware can be used to run the validator node. While Solana relies on 21 Solana experts for the operation of the network.
  - OpenGov
- Type 2 decisions of Polkadot:
  - Parachains would be long term applications-chains
  - Services and agile coretime changed taht viewpoint to also include applications that can spin-up and spin-down at will
  - Even though XCMP is a type 1 decision, the language is not (XCM). The language can be changed but the protocol can't
  - Treasury & Fellowship
### Philosophies of Polkadot
- Less trust more truth. Removing powerful incumbent, decentralizing the power
- Right now, it is hard to create a system that has no trust at all. We can only reduce the level of trust
- Against blockchain maximalism. Chain agnostic. Polkadot aims at becoming a one protocol for the whole network
- "The best blockchain today will not be the best blockchain tomorrow"
- Polkadot aims to be a blockchain that can last for hundred years instead of being the "go-to-market" products.
- Goals of Polkadot
  - Blockchain scalability trilemma: Security, Scalability, Decentralization. Have to sacrifire one of the key attributes to support the another twos.
  - Polkadot tries to solve as much as they can all the aspects of the trilemma.
  - Polkadot's mission is to provide secure, scalable and resilient infrastructure for Web3 applications and services
- Computatal scalability, interoperability, shared security
  - In Cosmos, each shard has its own security
- Code is Law, there is no large voice that can force the network to upgrade or not
- Polkadot has designed at its core a self-funded treasury pool to incentivize the development and evolution of the protocol
  - Trust-free system, without any middleman or authority, anyone can still fund for the development of the protocol

## Relevant Knowledge in the Gray Paper

```mermaid
mindmap
  Relevant to JAM Knowledge
    Polkadot 
      Independent Ecosystems
        Isolated Parachains
      Accessbility Limitations
        XCMP
      Composability
        SPREE
        Synchronous Composability
    Ethereum Scalability
      Data Availability
        Dank-sharding
      Roll-ups
        ZK-SNARK-based Roll-ups
        Heterogeneous Communication Properties
          Datagran
          Semantic Range
        Security Properties
          Cost of reversion
          Corruption
          Stalling
          Censorship
        Economic Properties
    Network Model
      High-Performance Fully Synchronous Networks
        Solana
          Structural Centralization
          Undermined Resilience
          Coherent Execution Model
      Fragmented Meta-Networks
        No Synchronous Composability
          Ethereum's Isolated Roll-up chains
          Polkadot's Isolated Parachains
        No Homogenous Security
          Cosmos
        Homogenous Consensus Mechanic
    Zero-knowledge Proofs
      SNARK
        Complexity
          Verification
          Computation
        RSIC-Zero
        SNARK Circuit
          Prover
          Verifier
        SNARK Proof
          Proof Generation
        Co-processor Model
```

## JAM Breakdown
### What is JAM?
- Unchanged
  - Philosophies of Polkadot
  - Goals of Polkadot
    - Parallel Execution and Heterogenous Sharding
    - Shared Security
    - Interoperability
- Changed
  - Upgradability of the core protocol
    - Substrate -> JAM chain
  - Services (as a superset of parachains)
  - WASM -> PolkaVM (RISC-V)
  - Synchronous Communication Capabilities
### Service Model

<img width="100%" alt="Screenshot 2024-04-26 at 14 09 51" src="https://github.com/openguild-labs/learn-jam/assets/56880684/85570a40-fde5-40f9-9fdb-8680a97e24ed">

## Gray Paper Notes
### About the limitations of Polkadot in its parachain model
<img width="100%" alt="Screenshot 2024-04-25 at 00 06 14" src="https://github.com/openguild-labs/awesome-jam/assets/56880684/1c218d5d-0dac-499b-9ee7-da881b5288f8">

### Data availability scaling in Ethereum
<img width="1233" alt="Screenshot 2024-04-25 at 00 08 12" src="https://github.com/openguild-labs/awesome-jam/assets/56880684/b3a0eeef-d91f-495f-8d59-267983f67180">

## Resources
- [JAM Gray Paper](https://graypaper.com/)
- [Polkadot Wiki - Learn JAM chain](https://wiki.polkadot.network/docs/learn-jam-chain)
- [CoreJAM RFC (by Polkadot Fellows)](https://github.com/polkadot-fellows/RFCs/blob/006a9ff07c3d3bc5316c6bf63b05e966e694cc2d/text/corejam.md)
- [sub0 Asia 2024 keynote - Gavin Wood on JAM A-Z](https://www.youtube.com/watch?v=tdvqkKdFTlw)


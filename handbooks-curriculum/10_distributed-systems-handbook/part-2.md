## Volume VI — Intermediate: Group Membership to Reasoning About Histories

**Learning Level:** Intermediate

**Theme**

Study how distributed systems manage dynamic membership, disseminate information efficiently, provide different consistency guarantees, and reason formally about concurrent operations and execution histories.

**Objective**

Develop a comprehensive understanding of membership management, gossip-based communication, consistency models, session guarantees, and formal history reasoning while learning how distributed systems coordinate dynamic clusters, propagate state, provide consistency guarantees, and verify correctness under concurrent execution.

---

## Part XXVI — Group Membership

**Purpose**

Study how distributed systems manage cluster membership by understanding joins, departures, failures, membership views, reconfiguration, incarnation numbers, and scalable membership protocols.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 338 | Static and Dynamic Membership | 📋 Planned |
| Chapter 339 | Joins | 📋 Planned |
| Chapter 340 | Leaves | 📋 Planned |
| Chapter 341 | Crashes | 📋 Planned |
| Chapter 342 | Membership Views | 📋 Planned |
| Chapter 343 | View Changes | 📋 Planned |
| Chapter 344 | Failure Dissemination | 📋 Planned |
| Chapter 345 | Reconfiguration | 📋 Planned |
| Chapter 346 | Incarnation Numbers | 📋 Planned |
| Chapter 347 | SWIM | 📋 Planned |
| Chapter 348 | Lifeguard-Style Ideas | 📋 Planned |
| Chapter 349 | Scalability | 📋 Planned |

---

## Part XXVII — Gossip and Epidemic Protocols

**Purpose**

Learn how large-scale distributed systems efficiently disseminate information through epidemic communication protocols by studying gossip algorithms, anti-entropy, convergence behavior, and scalable information propagation.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 350 | Epidemic Dissemination | 📋 Planned |
| Chapter 351 | Push, Pull, and Push-Pull Gossip | 📋 Planned |
| Chapter 352 | Rumor Mongering | 📋 Planned |
| Chapter 353 | Anti-Entropy | 📋 Planned |
| Chapter 354 | Fanout | 📋 Planned |
| Chapter 355 | Rounds | 📋 Planned |
| Chapter 356 | Convergence Probability | 📋 Planned |
| Chapter 357 | Membership State and Failure Gossip | 📋 Planned |
| Chapter 358 | Gossip Storms | 📋 Planned |

---

## Part XXVIII — Consistency Models

**Purpose**

Study the spectrum of consistency guarantees provided by distributed systems by understanding strong and weak consistency models, causality, eventual consistency, bounded staleness, and the trade-offs between correctness, availability, and performance.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 359 | Strict Consistency | 📋 Planned |
| Chapter 360 | Linearizability | 📋 Planned |
| Chapter 361 | Sequential Consistency | 📋 Planned |
| Chapter 362 | Causal Consistency | 📋 Planned |
| Chapter 363 | PRAM Consistency | 📋 Planned |
| Chapter 364 | FIFO Consistency | 📋 Planned |
| Chapter 365 | Processor Consistency | 📋 Planned |
| Chapter 366 | Eventual and Strong Eventual Consistency | 📋 Planned |
| Chapter 367 | Bounded Staleness | 📋 Planned |
| Chapter 368 | Prefix Consistency | 📋 Planned |
| Chapter 369 | Timeline Consistency | 📋 Planned |
| Chapter 370 | Tunable Consistency | 📋 Planned |

---

## Part XXIX — Client-Centric and Session Guarantees

**Purpose**

Learn the consistency guarantees experienced by individual clients by studying session semantics, client-centric consistency models, mobile clients, and mechanisms that preserve predictable application behavior across distributed systems.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 371 | Read-Your-Writes | 📋 Planned |
| Chapter 372 | Monotonic Reads and Writes | 📋 Planned |
| Chapter 373 | Writes-Follow-Reads | 📋 Planned |
| Chapter 374 | Session Consistency | 📋 Planned |
| Chapter 375 | Sticky and Causal Sessions | 📋 Planned |
| Chapter 376 | Mobile and Disconnected Clients | 📋 Planned |
| Chapter 377 | Session Tokens | 📋 Planned |

---

## Part XXX — Reasoning About Histories

**Purpose**

Develop the formal reasoning skills required to analyze distributed executions by studying operations, histories, linearization points, serialization graphs, concurrent behavior, and correctness anomalies.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 378 | Operations | 📋 Planned |
| Chapter 379 | Invocations | 📋 Planned |
| Chapter 380 | Responses | 📋 Planned |
| Chapter 381 | Concurrent Operations | 📋 Planned |
| Chapter 382 | Histories | 📋 Planned |
| Chapter 383 | Sequential Equivalent and Legal Histories | 📋 Planned |
| Chapter 384 | Linearization Points | 📋 Planned |
| Chapter 385 | Precedence and Serialization Graphs | 📋 Planned |
| Chapter 386 | Anomalies | 📋 Planned |
| Chapter 387 | Timelines | 📋 Planned |

---

## Volume VI Glossary

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 388 | Volume VI Glossary | 📋 Planned |

---

## Volume VI Summary

Volume VI introduces the mechanisms that allow distributed systems to operate as dynamic, scalable, and logically consistent clusters. Readers study group membership protocols, gossip-based dissemination, the complete spectrum of distributed consistency models, client-centric consistency guarantees, and the formal methods used to reason about concurrent histories. By mastering these concepts, readers gain the theoretical foundation required to understand distributed databases, transaction processing, concurrency control, and correctness verification throughout the remainder of the handbook.

---

## Volume VII — Intermediate: Testing Consistency to Hotspots and Skew

**Learning Level:** Intermediate

**Theme**

Study how distributed systems are validated, partitioned, rebalanced, and optimized by understanding correctness testing, verification techniques, sharding architectures, data movement, and workload skew mitigation.

**Objective**

Develop a comprehensive understanding of distributed correctness verification, consistency testing, partitioning strategies, resharding operations, and hotspot mitigation while learning how modern distributed systems maintain correctness, scalability, and balanced performance under real-world workloads.

---

## Part XXXI — Testing Consistency

**Purpose**

Study how distributed systems are tested for correctness by understanding history recording, fault injection, workload generation, consistency verification, and modern testing methodologies for distributed environments.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 389 | Linearizability and Serializability Checking | 📋 Planned |
| Chapter 390 | History Recording | 📋 Planned |
| Chapter 391 | Workloads | 📋 Planned |
| Chapter 392 | Nemeses | 📋 Planned |
| Chapter 393 | Network and Clock Faults | 📋 Planned |
| Chapter 394 | Jepsen-Style Testing | 📋 Planned |
| Chapter 395 | Elle-Style Analysis Context | 📋 Planned |
| Chapter 396 | False Conclusions | 📋 Planned |
| Chapter 397 | Test Design | 📋 Planned |

---

## Part XXXII — Distributed Verification, History Reduction, and Correctness Oracles

**Purpose**

Learn the advanced techniques used to verify distributed system correctness by studying correctness oracles, history reduction, anomaly detection, verification architectures, differential testing, and production correctness monitoring.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 398 | Correctness Oracles | 📋 Planned |
| Chapter 399 | Online versus Offline Verification | 📋 Planned |
| Chapter 400 | History Reduction | 📋 Planned |
| Chapter 401 | Operation Dependency Graphs | 📋 Planned |
| Chapter 402 | Cycle Detection for Anomalies | 📋 Planned |
| Chapter 403 | Minimal Counterexamples | 📋 Planned |
| Chapter 404 | Linearizability Checker Architecture | 📋 Planned |
| Chapter 405 | Serializability Checker Architecture | 📋 Planned |
| Chapter 406 | Consistency Model Litmus Tests | 📋 Planned |
| Chapter 407 | Metamorphic Testing for Distributed Systems | 📋 Planned |
| Chapter 408 | Differential Testing of Replicas | 📋 Planned |
| Chapter 409 | Shadow Traffic Verification | 📋 Planned |
| Chapter 410 | Production Invariant Monitoring | 📋 Planned |
| Chapter 411 | False Positives and Incomplete Histories | 📋 Planned |
| Chapter 412 | Building a Distributed Correctness Harness | 📋 Planned |

---

## Part XXXIII — Partitioning and Sharding

**Purpose**

Study how distributed systems partition data across multiple nodes by understanding partitioning strategies, consistent hashing, partition maps, and scalable data placement techniques.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 413 | Horizontal, Range, Hash, and Directory Partitioning | 📋 Planned |
| Chapter 414 | Consistent Hashing | 📋 Planned |
| Chapter 415 | Hash Rings | 📋 Planned |
| Chapter 416 | Virtual Nodes | 📋 Planned |
| Chapter 417 | Rendezvous Hashing | 📋 Planned |
| Chapter 418 | Jump Hashing Context | 📋 Planned |
| Chapter 419 | Geo and Composite Partitioning | 📋 Planned |
| Chapter 420 | Partition Maps | 📋 Planned |

---

## Part XXXIV — Rebalancing and Resharding

**Purpose**

Learn how distributed systems evolve as clusters grow and shrink by studying shard migration, online resharding, metadata consistency, cutovers, forwarding, and operational strategies for minimizing disruption during data movement.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 421 | Node Addition and Removal | 📋 Planned |
| Chapter 422 | Shard Movement | 📋 Planned |
| Chapter 423 | Online Resharding | 📋 Planned |
| Chapter 424 | Split and Merge | 📋 Planned |
| Chapter 425 | Range Movement | 📋 Planned |
| Chapter 426 | Migration Dual Writes | 📋 Planned |
| Chapter 427 | Cutovers | 📋 Planned |
| Chapter 428 | Forwarding | 📋 Planned |
| Chapter 429 | Metadata Consistency | 📋 Planned |
| Chapter 430 | Storms | 📋 Planned |
| Chapter 431 | Throttling | 📋 Planned |

---

## Part XXXV — Hotspots and Skew

**Purpose**

Study workload imbalance in distributed systems by understanding hotspot formation, skew detection, adaptive partitioning, load-aware placement, and techniques for mitigating uneven traffic distribution.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 432 | Hot Keys and Shards | 📋 Planned |
| Chapter 433 | Celebrity Workloads | 📋 Planned |
| Chapter 434 | Temporal and Sequential-Key Hotspots | 📋 Planned |
| Chapter 435 | Skew Detection | 📋 Planned |
| Chapter 436 | Key Splitting | 📋 Planned |
| Chapter 437 | Salting | 📋 Planned |
| Chapter 438 | Adaptive Partitioning | 📋 Planned |
| Chapter 439 | Load-Aware Placement | 📋 Planned |
| Chapter 440 | Request Coalescing | 📋 Planned |
| Chapter 441 | Mitigation | 📋 Planned |

---

## Volume VII Glossary

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 442 | Volume VII Glossary | 📋 Planned |

---

## Volume VII Summary

Volume VII focuses on validating correctness and achieving scalable data distribution in distributed systems. Readers study consistency testing, formal verification techniques, correctness oracles, history analysis, partitioning architectures, shard management, online resharding, and hotspot mitigation strategies. By mastering verification methodologies and scalable partitioning techniques, readers learn how distributed systems maintain correctness while efficiently distributing workloads and adapting to continuously changing cluster conditions.

---

## Volume VIII — Intermediate: Distributed Storage Foundations to Distributed Key-Value Stores

**Learning Level:** Intermediate

**Theme**

Study the architecture of distributed storage systems by understanding storage abstractions, distributed file systems, object storage, erasure coding, and distributed key-value stores that power modern cloud infrastructure.

**Objective**

Develop a comprehensive understanding of distributed storage architectures by learning how modern systems store, replicate, protect, repair, and retrieve data across large-scale clusters while exploring the engineering principles behind distributed file systems, object storage platforms, erasure coding, and distributed key-value databases.

---

## Part XXXVI — Distributed Storage Foundations

**Purpose**

Study the fundamental storage abstractions used in distributed systems by understanding storage models, metadata management, durability, placement strategies, replication, erasure coding, and degraded operation.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 443 | Distributed Block, File, Object, Key-Value, and Content-Addressed Storage | 📋 Planned |
| Chapter 444 | Metadata and Data Planes | 📋 Planned |
| Chapter 445 | Durability | 📋 Planned |
| Chapter 446 | Placement | 📋 Planned |
| Chapter 447 | Replication | 📋 Planned |
| Chapter 448 | Erasure Coding | 📋 Planned |
| Chapter 449 | Repair | 📋 Planned |
| Chapter 450 | Degraded Operation | 📋 Planned |

---

## Part XXXVII — Distributed File Systems

**Purpose**

Learn how distributed file systems organize, replicate, and manage large-scale data by studying namespaces, metadata services, chunk storage, locality, replication, and scalable file system architectures.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 451 | Namespaces | 📋 Planned |
| Chapter 452 | Metadata Servers | 📋 Planned |
| Chapter 453 | Chunk Servers | 📋 Planned |
| Chapter 454 | Blocks and Chunks | 📋 Planned |
| Chapter 455 | GFS and HDFS-Style Systems | 📋 Planned |
| Chapter 456 | Leases | 📋 Planned |
| Chapter 457 | Append Semantics | 📋 Planned |
| Chapter 458 | Locality | 📋 Planned |
| Chapter 459 | Replication | 📋 Planned |
| Chapter 460 | Checksums | 📋 Planned |
| Chapter 461 | Re-Replication | 📋 Planned |
| Chapter 462 | Small Files | 📋 Planned |
| Chapter 463 | Metadata Scaling | 📋 Planned |

---

## Part XXXVIII — Distributed Object Storage

**Purpose**

Study object storage architectures by understanding object models, namespaces, placement algorithms, replication strategies, erasure coding, consistency models, and large-scale object storage platforms.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 464 | Objects | 📋 Planned |
| Chapter 465 | Buckets | 📋 Planned |
| Chapter 466 | Namespaces | 📋 Planned |
| Chapter 467 | Object IDs | 📋 Planned |
| Chapter 468 | Immutability | 📋 Planned |
| Chapter 469 | Mutable Metadata | 📋 Planned |
| Chapter 470 | Placement Groups | 📋 Planned |
| Chapter 471 | CRUSH-Style Placement | 📋 Planned |
| Chapter 472 | RADOS-Style Systems | 📋 Planned |
| Chapter 473 | Replication | 📋 Planned |
| Chapter 474 | Erasure Coding | 📋 Planned |
| Chapter 475 | Multipart Upload | 📋 Planned |
| Chapter 476 | Consistency | 📋 Planned |
| Chapter 477 | Scrubbing | 📋 Planned |
| Chapter 478 | Repair | 📋 Planned |

---

## Part XXXIX — Erasure Coding

**Purpose**

Understand how distributed storage systems achieve durability with lower storage overhead by studying parity, Reed-Solomon coding, degraded reads, repair algorithms, and modern erasure coding techniques.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 479 | Replication Cost | 📋 Planned |
| Chapter 480 | Parity Intuition | 📋 Planned |
| Chapter 481 | XOR | 📋 Planned |
| Chapter 482 | Reed-Solomon Concepts | 📋 Planned |
| Chapter 483 | K+m Layouts | 📋 Planned |
| Chapter 484 | Encoding | 📋 Planned |
| Chapter 485 | Reconstruction | 📋 Planned |
| Chapter 486 | Degraded Reads | 📋 Planned |
| Chapter 487 | Repair Bandwidth | 📋 Planned |
| Chapter 488 | Local Reconstruction Codes | 📋 Planned |
| Chapter 489 | Geo-Erasure Coding | 📋 Planned |
| Chapter 490 | Acceleration | 📋 Planned |

---

## Part XL — Distributed Key-Value Stores

**Purpose**

Study the architecture of distributed key-value databases by understanding APIs, partitioning, replication, routing, membership, metadata management, consistency models, repair mechanisms, and real-world distributed KV systems.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 491 | APIs | 📋 Planned |
| Chapter 492 | Partitioning | 📋 Planned |
| Chapter 493 | Replication | 📋 Planned |
| Chapter 494 | Routing | 📋 Planned |
| Chapter 495 | Coordinators | 📋 Planned |
| Chapter 496 | Metadata | 📋 Planned |
| Chapter 497 | Membership | 📋 Planned |
| Chapter 498 | Consistency | 📋 Planned |
| Chapter 499 | Compaction Context | 📋 Planned |
| Chapter 500 | Repair | 📋 Planned |
| Chapter 501 | Dynamo and Cassandra-Style Systems | 📋 Planned |
| Chapter 502 | Build a KV Store | 📋 Planned |

---

## Volume VIII Glossary

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 503 | Volume VIII Glossary | 📋 Planned |

---

## Volume VIII Summary

Volume VIII introduces the core storage architectures that underpin modern distributed systems. Readers study distributed storage foundations, distributed file systems, object storage platforms, erasure coding, and distributed key-value stores. By understanding storage abstractions, metadata management, data placement, replication, durability mechanisms, repair strategies, and scalable storage architectures, readers gain the knowledge required to design and operate reliable, highly available, and efficient distributed storage systems used throughout modern cloud infrastructure.

---

## Volume IX — Intermediate: Distributed Transactions Foundations to Distributed Concurrency Control

**Learning Level:** Intermediate

**Theme**

Study how distributed systems execute reliable transactions across multiple nodes by understanding atomic commitment, distributed transaction protocols, concurrency control, recovery mechanisms, and coordination algorithms that preserve correctness in the presence of failures.

**Objective**

Develop a comprehensive understanding of distributed transaction processing by learning how atomic commitment protocols, distributed concurrency control mechanisms, recovery techniques, and coordination algorithms ensure consistency, isolation, durability, and correctness across large-scale distributed systems.

---

## Part XLI — Distributed Transactions Foundations

**Purpose**

Study the core principles of distributed transactions by understanding atomic commitment, coordinators, participants, recovery logs, transaction lifecycles, and the challenges introduced by failures and uncertainty in distributed environments.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 504 | Local vs Distributed Transactions | 📋 Planned |
| Chapter 505 | Atomic Commitment | 📋 Planned |
| Chapter 506 | Distributed Atomicity | 📋 Planned |
| Chapter 507 | Coordinator State | 📋 Planned |
| Chapter 508 | Participants | 📋 Planned |
| Chapter 509 | Uncertainty | 📋 Planned |
| Chapter 510 | In-Doubt Transactions | 📋 Planned |
| Chapter 511 | Transaction IDs | 📋 Planned |
| Chapter 512 | Recovery Logs | 📋 Planned |
| Chapter 513 | Failure Matrices | 📋 Planned |

---

## Part XLII — Two-Phase Commit

**Purpose**

Learn how Two-Phase Commit (2PC) coordinates distributed transactions by studying prepare and commit phases, coordinator and participant behavior, recovery mechanisms, blocking problems, and practical implementation techniques.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 514 | Prepare | 📋 Planned |
| Chapter 515 | Voting | 📋 Planned |
| Chapter 516 | Commit | 📋 Planned |
| Chapter 517 | Abort | 📋 Planned |
| Chapter 518 | Coordinator and Participant Logs | 📋 Planned |
| Chapter 519 | Crash Before and After Prepare | 📋 Planned |
| Chapter 520 | Coordinator Failure | 📋 Planned |
| Chapter 521 | Blocking | 📋 Planned |
| Chapter 522 | Recovery | 📋 Planned |
| Chapter 523 | Presumed Abort | 📋 Planned |
| Chapter 524 | Presumed Commit | 📋 Planned |
| Chapter 525 | Implementation | 📋 Planned |

---

## Part XLIII — Three-Phase Commit and Atomic Commitment

**Purpose**

Study advanced atomic commitment protocols by understanding Three-Phase Commit, non-blocking assumptions, consensus-backed coordination, and the relationship between atomic commitment and distributed consensus.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 526 | Three-Phase Commit (3PC) | 📋 Planned |
| Chapter 527 | Non-Blocking Assumptions | 📋 Planned |
| Chapter 528 | Pre-Commit | 📋 Planned |
| Chapter 529 | Failure Assumptions | 📋 Planned |
| Chapter 530 | Partitions | 📋 Planned |
| Chapter 531 | Practical Limits | 📋 Planned |
| Chapter 532 | Consensus-Backed Commit | 📋 Planned |
| Chapter 533 | Atomic Commitment vs Consensus | 📋 Planned |
| Chapter 534 | Modern Coordination | 📋 Planned |

---

## Part XLIV — Distributed Concurrency Control

**Purpose**

Study how distributed systems preserve isolation and correctness under concurrent execution by understanding locking protocols, timestamp ordering, optimistic concurrency control, MVCC, deadlock management, and distributed serialization techniques.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 535 | Distributed Locks and Two-Phase Locking (2PL) | 📋 Planned |
| Chapter 536 | Timestamps | 📋 Planned |
| Chapter 537 | Optimistic Concurrency | 📋 Planned |
| Chapter 538 | Distributed MVCC | 📋 Planned |
| Chapter 539 | Validation | 📋 Planned |
| Chapter 540 | Deadlocks | 📋 Planned |
| Chapter 541 | Wait-for Graphs | 📋 Planned |
| Chapter 542 | Detection | 📋 Planned |
| Chapter 543 | Prevention | 📋 Planned |
| Chapter 544 | Distributed Serialization | 📋 Planned |

---

## Volume IX Glossary

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 545 | Volume IX Glossary | 📋 Planned |

---

## Volume IX Summary

Volume IX establishes the foundations of distributed transaction processing by introducing distributed atomicity, commitment protocols, transaction recovery, and concurrency control. Readers study Two-Phase Commit, Three-Phase Commit, consensus-backed transaction coordination, distributed locking, MVCC, optimistic concurrency control, deadlock management, and serialization techniques. Together, these topics provide the essential transactional foundation required to build reliable distributed databases and strongly consistent distributed applications.

---

**End of Part II — Distributed Storage and Transaction Systems**

This concludes **Part II** of the **Distributed Systems Engineer's Handbook**, covering the engineering foundations of distributed storage architectures, distributed file systems, object storage, erasure coding, distributed key-value stores, distributed transactions, atomic commitment protocols, and distributed concurrency control. Readers have also developed a strong understanding of consistency verification, partitioning, sharding, rebalancing, hotspot mitigation, and the core storage and transaction mechanisms that underpin modern distributed databases and cloud-scale data platforms.

With these intermediate foundations established, the handbook now progresses into **Part III — Distributed Databases and Data Processing Systems**, where readers will study distributed SQL and NoSQL databases, replication architectures, log-structured storage engines, indexing strategies, stream processing, messaging systems, event-driven architectures, distributed query processing, and the large-scale data systems that power modern cloud-native applications.

The next document,

**part-3.md**

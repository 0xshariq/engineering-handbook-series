## Volume XX — Expert / Research

**Learning Level:** Expert / Research

**Theme**

Linux Boot Images, Unified Kernel Images, and Image-Based Host Delivery → Linux Control Group v2 Delegation and Modern Resource Governance

**Objective**

Develop a research-level understanding of modern Linux host lifecycle engineering by exploring unified kernel images, image-based operating system delivery, transactional updates, advanced cgroup v2 resource governance, and the mechanisms that enable secure, manageable, cloud-scale Linux infrastructures.

---

### Part LXII — Linux Boot Images, Unified Kernel Images, and Image-Based Host Delivery

**Purpose**

Understand the evolution of Linux boot architecture from traditional initramfs generation to unified kernel images, image-based operating systems, transactional updates, and lifecycle management for modern Linux hosts.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 1589 — dracut and Initramfs Generation Architecture | Understand modular initramfs generation using dracut.  📋 Planned |
| Chapter 1590 — systemd-stub Boot Stub Architecture | Learn how systemd-stub enables Unified Kernel Images.  📋 Planned |
| Chapter 1591 — Kernel, Initrd, Command Line, and Metadata in a UKI | Explore the structure of a Unified Kernel Image.  📋 Planned |
| Chapter 1592 — Measured Boot with Unified Kernel Images | Understand trusted boot verification using UKIs.  📋 Planned |
| Chapter 1593 — systemd-sysext System Extensions | Learn runtime operating system extension mechanisms.  📋 Planned |
| Chapter 1594 — systemd-confext Configuration Extensions | Explore configuration layering for immutable systems.  📋 Planned |
| Chapter 1595 — bootc Transactional Image-Based OS Updates | Understand image-based operating system updates using bootc.  📋 Planned |
| Chapter 1596 — composefs Verified and Shareable Filesystem Images | Learn verified filesystem image composition.  📋 Planned |
| Chapter 1597 — Image-Based Linux Host Lifecycle Engineering | Explore lifecycle management for image-based Linux hosts.  📋 Planned |
| Chapter 1598 — Atomic Host Rollback and Update Health Validation | Understand safe rollback strategies and update verification.  📋 Planned |

---

### Part LXIII — Linux Control Group v2 Delegation and Modern Resource Governance

**Purpose**

Develop an expert understanding of cgroup v2 as Linux's unified resource governance framework by exploring delegation, hierarchical resource control, memory protection, CPU scheduling, and modern workload isolation.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 1599 — cgroup v2 Unified Hierarchy Revisited | Revisit the architecture and principles of the unified hierarchy.  📋 Planned |
| Chapter 1600 — cgroup v2 Delegation Model | Understand safe delegation of resource management.  📋 Planned |
| Chapter 1601 — Delegation Boundaries and Ownership | Learn ownership rules within delegated resource hierarchies.  📋 Planned |
| Chapter 1602 — Threaded Cgroups | Explore threaded resource control groups.  📋 Planned |
| Chapter 1603 — No-Internal-Process Constraint | Understand structural constraints within cgroup v2.  📋 Planned |
| Chapter 1604 — Controller Enablement Semantics | Learn how controllers are enabled and propagated.  📋 Planned |
| Chapter 1605 — systemd Resource Control and cgroup v2 | Explore systemd integration with unified resource management.  📋 Planned |
| Chapter 1606 — Pressure Stall Information for Resource Governance | Understand PSI-driven adaptive resource management.  📋 Planned |
| Chapter 1607 — Memory Protection with memory.low and memory.min | Learn workload protection using memory guarantees.  📋 Planned |
| Chapter 1608 — Memory Throttling with memory.high | Explore controlled memory pressure management.  📋 Planned |
| Chapter 1609 — CPU Weight, Quota, and Burst Controls | Understand proportional and quota-based CPU allocation.  📋 Planned |
| Chapter 1610 — I/O Cost and Weight Control | Learn storage resource governance in Linux.  📋 Planned |
| Chapter 1611 — Resource Governance for Rootless Workloads | Explore secure resource management for unprivileged environments.  📋 Planned |

---

## Volume XX Glossary

**Chapter 1612 — Volume XX Glossary**

A concise reference covering Unified Kernel Images, dracut, systemd-stub, bootc, composefs, image-based operating systems, cgroup v2, delegation, resource governance, PSI, memory controllers, CPU scheduling controls, and workload isolation.

---

### Volume XX Summary

Volume XX explores the next generation of Linux host engineering. Readers learn how image-based operating systems, Unified Kernel Images, transactional updates, and cgroup v2 enable secure, scalable, and highly manageable Linux infrastructures. This volume demonstrates how modern Linux is evolving toward immutable, policy-driven, cloud-native operating system design.

---

## Volume XXI — Advanced

**Learning Level:** Advanced

**Theme**

Linux Security Framework Composition and Self-Protection

**Objective**

Develop a comprehensive understanding of how Linux security mechanisms interact as a unified defensive architecture by exploring Linux Security Module composition, kernel self-protection, sandboxing, integrity enforcement, and attack surface reduction strategies.

---

### Part LXIV — Linux Security Framework Composition and Self-Protection

**Purpose**

Understand Linux security as a layered architecture by exploring how multiple security frameworks cooperate to provide defense in depth while maintaining flexibility, compatibility, and long-term system integrity.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 1613 — LSM Stacking and Security Module Composition | Understand how multiple Linux Security Modules coexist within the kernel.  📋 Planned |
| Chapter 1614 — BPF LSM Architecture | Explore programmable security policies using eBPF-based Linux Security Modules.  📋 Planned |
| Chapter 1615 — Landlock Rulesets and Unprivileged Sandboxing | Learn application sandboxing through Landlock security policies.  📋 Planned |
| Chapter 1616 — Integrity Policy Enforcement Context | Understand policy-driven integrity verification within Linux.  📋 Planned |
| Chapter 1617 — Kernel Self-Protection Project Principles | Explore the principles guiding Linux kernel self-protection efforts.  📋 Planned |
| Chapter 1618 — Attack Surface Reduction in Kernel Configuration | Learn techniques for minimizing kernel attack surfaces.  📋 Planned |
| Chapter 1619 — Kernel Memory Sealing with mseal Context | Understand emerging memory sealing mechanisms for application protection.  📋 Planned |
| Chapter 1620 — No New Privileges as a Security Primitive | Explore privilege restriction as a fundamental Linux security mechanism.  📋 Planned |
| Chapter 1621 — seccomp User Notification | Learn interactive system call filtering and userspace mediation.  📋 Planned |
| Chapter 1622 — Kernel Lockdown and Trust Boundaries | Understand kernel lockdown modes and trusted execution boundaries.  📋 Planned |
| Chapter 1623 — Security Policy Composition Failure Modes | Analyze conflicts and limitations when combining multiple Linux security frameworks.  📋 Planned |

---

## Volume XXI Glossary

**Chapter 1624 — Volume XXI Glossary**

A concise reference covering Linux Security Modules, BPF LSM, Landlock, integrity enforcement, kernel self-protection, mseal, seccomp user notification, kernel lockdown, layered security architectures, and Linux defense-in-depth principles.

---

### Volume XXI Summary

Volume XXI concludes Markdown Part 7 by exploring Linux security as a composed system rather than a collection of isolated technologies. Readers learn how modern Linux integrates multiple security frameworks, kernel hardening techniques, programmable security policies, and self-protection mechanisms into a cohesive defensive architecture capable of securing production workloads across diverse computing environments.

---

## Volume XXII — Expert / Research

**Learning Level:** Expert / Research

**Theme**

Linux Real-Time Analysis and Latency Tooling → Linux Checkpoint, Restore, Live Migration, and Runtime Continuity

**Objective**

Master the tooling, testing infrastructure, and runtime continuity technologies that enable Linux to operate reliably in production, real-time, cloud-native, and mission-critical environments. By completing this volume, readers will understand how Linux engineers measure latency, validate kernel correctness, detect regressions, migrate running workloads, and preserve execution state across systems.

---

### Part LXV — Linux Real-Time Analysis and Latency Tooling

**Purpose**

Develop an engineering methodology for measuring, diagnosing, and minimizing latency in real-time Linux systems using modern tracing frameworks and performance analysis tools.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 1625 — rtla Real-Time Linux Analysis Toolkit | Learn the Linux Real-Time Linux Analysis toolkit for latency diagnostics.  📋 Planned |
| Chapter 1626 — osnoise Tracer | Understand operating system noise measurement and analysis.  📋 Planned |
| Chapter 1627 — timerlat Tracer | Explore timer latency measurement in deterministic systems.  📋 Planned |
| Chapter 1628 — Hardware Noise and OS Noise Separation | Differentiate hardware-induced latency from operating system scheduling delays.  📋 Planned |
| Chapter 1629 — IRQ and Threaded Interrupt Latency Analysis | Analyze interrupt latency in PREEMPT_RT environments.  📋 Planned |
| Chapter 1630 — PREEMPT_RT Latency Regression Investigation | Learn systematic diagnosis of real-time performance regressions.  📋 Planned |
| Chapter 1631 — CPU Isolation and Housekeeping Diagnostics | Explore workload isolation and housekeeping CPU verification.  📋 Planned |
| Chapter 1632 — Real-Time Scheduling Failure Analysis | Investigate scheduling anomalies affecting deterministic execution.  📋 Planned |

---

### Part LXVI — Linux Kernel Testing, Sanitizers, and Regression Infrastructure

**Purpose**

Understand the infrastructure that ensures Linux kernel correctness through automated testing, sanitizers, regression detection, fuzzing, and continuous validation across diverse hardware platforms.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 1633 — KUnit Kernel Unit Testing Architecture | Learn unit testing within the Linux kernel.  📋 Planned |
| Chapter 1634 — kselftest Userspace and Kernel Interface Testing | Explore automated validation of kernel interfaces.  📋 Planned |
| Chapter 1635 — Kernel Test Anything Protocol | Understand standardized kernel test reporting.  📋 Planned |
| Chapter 1636 — KMSAN Kernel Memory Sanitizer | Learn runtime detection of uninitialized memory usage.  📋 Planned |
| Chapter 1637 — KFENCE Low-Overhead Heap Error Detection | Explore lightweight heap corruption detection.  📋 Planned |
| Chapter 1638 — KCSAN Data Race Detection | Understand automated race-condition detection.  📋 Planned |
| Chapter 1639 — KASAN Revisited for Kernel Memory Bugs | Learn advanced memory safety verification within Linux.  📋 Planned |
| Chapter 1640 — Lockdep Dependency Validation | Explore kernel locking correctness analysis.  📋 Planned |
| Chapter 1641 — Fault Injection Frameworks | Understand controlled fault generation for robustness testing.  📋 Planned |
| Chapter 1642 — Kernel CI and Hardware Lab Automation | Learn continuous integration across diverse Linux hardware.  📋 Planned |
| Chapter 1643 — Boot Regression Testing | Explore automated validation of Linux boot reliability.  📋 Planned |
| Chapter 1644 — Performance Regression Bisection | Identify performance regressions using systematic isolation techniques.  📋 Planned |
| Chapter 1645 — ABI and UAPI Regression Testing | Verify long-term compatibility of Linux interfaces.  📋 Planned |
| Chapter 1646 — Syzkaller Reproduction and Crash Deduplication | Understand automated kernel fuzzing, crash analysis, and bug triage.  📋 Planned |

---

### Part LXVII — Linux Checkpoint, Restore, Live Migration, and Runtime Continuity

**Purpose**

Explore Linux runtime continuity technologies that enable workload migration, process checkpointing, state preservation, disaster recovery, and highly available distributed computing.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 1647 — CRIU Architecture | Understand the architecture of Checkpoint/Restore In Userspace.  📋 Planned |
| Chapter 1648 — Freezing Linux Process Trees | Learn techniques for suspending complex process hierarchies.  📋 Planned |
| Chapter 1649 — Checkpointing Linux Namespaces and Cgroups | Explore state preservation for isolated Linux workloads.  📋 Planned |
| Chapter 1650 — Checkpointing File Descriptors and Sockets | Understand restoration of active communication channels.  📋 Planned |
| Chapter 1651 — Incremental Pre-Dump | Learn staged checkpoint creation for minimal downtime.  📋 Planned |
| Chapter 1652 — Lazy Page Restore with userfaultfd | Explore demand-driven memory restoration during workload migration.  📋 Planned |
| Chapter 1653 — Container Live Migration | Understand migration of running containerized workloads.  📋 Planned |
| Chapter 1654 — Kernel Compatibility Constraints in Restore | Learn compatibility challenges during workload restoration.  📋 Planned |
| Chapter 1655 — Checkpoint Security and Secret State | Explore secure preservation of sensitive runtime information.  📋 Planned |
| Chapter 1656 — Linux Workload Continuity Across Hosts | Integrate checkpoint, migration, and recovery technologies into resilient Linux infrastructures.  📋 Planned |

---

## Volume XXII Glossary

**Chapter 1657 — Volume XXII Glossary**

A concise reference covering rtla, osnoise, timerlat, PREEMPT_RT analysis, KUnit, kselftest, kernel sanitizers, Lockdep, Syzkaller, CRIU, checkpoint and restore, live migration, runtime continuity, and Linux reliability engineering.

---

### Volume XXII Summary

Volume XXII concludes the Linux Engineering Handbook by focusing on Linux reliability engineering. Readers learn how modern Linux systems are analyzed, tested, validated, migrated, and maintained under demanding production conditions. The volume unifies real-time latency analysis, kernel testing infrastructure, regression detection, workload checkpointing, and runtime continuity into a complete engineering methodology for building resilient Linux platforms.

---

# Linux Engineering Handbook Curriculum Complete

With the completion of **Volume XXII**, the **Linux Engineering Handbook** curriculum reaches its conclusion.

Across **22 volumes**, **67 parts**, and **1,657 chapters**, the handbook progresses from the historical foundations of Linux through kernel architecture, operating system internals, storage, networking, security, performance engineering, virtualization, distribution engineering, modern kernel interfaces, enterprise Linux ecosystems, real-time systems, confidential computing, immutable operating systems, kernel development, and advanced research topics.

The curriculum is intentionally structured to move from foundational knowledge to production engineering and finally to research-level topics, ensuring that readers build intuition before implementation and master Linux as a complete operating system engineering discipline rather than a collection of commands or administration techniques.

This completes the planned curriculum for the **Linux Engineering Handbook**.

*Last Updated: July 2026*
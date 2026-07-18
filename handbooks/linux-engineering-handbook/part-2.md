## Volume IV — Intermediate

**Learning Level:** Intermediate

**Theme**

Linux Memory Engineering → Linux Logging

**Objective**

Build a deep understanding of Linux memory management, kernel resource isolation, modern service management with systemd, and enterprise logging infrastructure. By completing this volume, readers will understand how Linux efficiently manages memory, isolates workloads, controls system resources, initializes services, and records system activity for monitoring, debugging, and incident response.

---

### Part XIV — Linux Memory Engineering

**Purpose**

Understand how Linux discovers, allocates, manages, optimizes, and reclaims memory while exploring modern memory management techniques for performance, scalability, and reliability.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 363 — Linux Memory Architecture | Understand the overall architecture of memory management in Linux.  📋 Planned |
| Chapter 364 — Physical Memory Discovery | Learn how Linux discovers physical memory during system startup.  📋 Planned |
| Chapter 365 — Memory Zones | Understand the purpose of memory zones within the kernel.  📋 Planned |
| Chapter 366 — NUMA | Explore Non-Uniform Memory Access and its impact on performance.  📋 Planned |
| Chapter 367 — Pages | Learn the fundamental memory unit used by Linux.  📋 Planned |
| Chapter 368 — Folios | Understand the modern folio abstraction introduced for memory management.  📋 Planned |
| Chapter 369 — Buddy Allocator | Explore Linux's primary physical memory allocator.  📋 Planned |
| Chapter 370 — SLAB History | Understand the evolution of Linux slab allocation.  📋 Planned |
| Chapter 371 — SLUB Allocator | Learn the architecture of the modern SLUB allocator.  📋 Planned |
| Chapter 372 — Kernel Memory Allocation | Understand dynamic memory allocation inside the kernel.  📋 Planned |
| Chapter 373 — User-Space Virtual Memory | Learn how Linux provides virtual memory to applications.  📋 Planned |
| Chapter 374 — Anonymous Memory | Explore anonymous memory allocation and usage.  📋 Planned |
| Chapter 375 — File-Backed Memory | Understand memory backed by filesystem objects.  📋 Planned |
| Chapter 376 — Page Cache | Learn how the page cache improves filesystem performance.  📋 Planned |
| Chapter 377 — mmap | Understand memory-mapped file access and shared memory.  📋 Planned |
| Chapter 378 — Copy-on-Write | Explore copy-on-write memory optimization.  📋 Planned |
| Chapter 379 — Memory Reclaim | Learn how Linux recovers memory under pressure.  📋 Planned |
| Chapter 380 — LRU Concepts | Understand least recently used memory management strategies.  📋 Planned |
| Chapter 381 — Swap and Reclaim | Explore swapping and page reclamation mechanisms.  📋 Planned |
| Chapter 382 — Memory Overcommit | Learn Linux memory overcommit policies.  📋 Planned |
| Chapter 383 — OOM Killer | Understand out-of-memory detection and recovery.  📋 Planned |
| Chapter 384 — HugeTLB Pages | Explore explicit huge page management.  📋 Planned |
| Chapter 385 — Transparent Huge Pages | Learn automatic huge page optimization.  📋 Planned |
| Chapter 386 — Memory Compaction | Understand memory defragmentation techniques.  📋 Planned |
| Chapter 387 — Memory Pressure Stall Information | Learn how Linux measures memory pressure.  📋 Planned |
| Chapter 388 — Memory cgroups | Understand memory isolation using cgroups.  📋 Planned |
| Chapter 389 — NUMA Memory Policy | Explore NUMA-aware memory allocation strategies.  📋 Planned |
| Chapter 390 — Memory Hotplug | Learn dynamic memory addition and removal.  📋 Planned |
| Chapter 391 — DAMON | Understand Data Access MONitor for workload-aware optimization.  📋 Planned |
| Chapter 392 — Diagnosing Linux Memory Problems | Develop practical techniques for troubleshooting memory-related issues.  📋 Planned |

---

### Part XV — Linux Namespaces

**Purpose**

Understand the kernel isolation mechanisms that form the foundation of Linux containers by exploring namespace architecture, resource isolation, and secure process separation.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 393 — The Isolation Problem | Understand why operating systems require resource isolation.  📋 Planned |
| Chapter 394 — Namespace History | Explore the evolution of Linux namespaces.  📋 Planned |
| Chapter 395 — Namespace Kernel Model | Learn the kernel architecture behind namespaces.  📋 Planned |
| Chapter 396 — Mount Namespaces | Understand filesystem isolation.  📋 Planned |
| Chapter 397 — PID Namespaces | Learn process identifier isolation.  📋 Planned |
| Chapter 398 — Network Namespaces | Explore isolated network stacks.  📋 Planned |
| Chapter 399 — UTS Namespaces | Understand hostname and domain isolation.  📋 Planned |
| Chapter 400 — IPC Namespaces | Learn inter-process communication isolation.  📋 Planned |
| Chapter 401 — User Namespaces | Explore unprivileged namespace capabilities.  📋 Planned |
| Chapter 402 — Cgroup Namespaces | Understand cgroup namespace virtualization.  📋 Planned |
| Chapter 403 — Time Namespaces | Learn Linux time virtualization.  📋 Planned |
| Chapter 404 — clone() and Namespaces | Understand namespace creation using clone().  📋 Planned |
| Chapter 405 — unshare() | Learn namespace separation from existing processes.  📋 Planned |
| Chapter 406 — setns() | Explore joining existing namespaces.  📋 Planned |
| Chapter 407 — Inspecting Namespaces | Learn techniques for namespace inspection.  📋 Planned |
| Chapter 408 — Namespace Security Boundaries | Understand security considerations for namespace isolation.  📋 Planned |
| Chapter 409 — Building an Isolated Process Environment | Combine namespaces to create isolated execution environments.  📋 Planned |

### Part XVI — Linux Control Groups

**Purpose**

Understand how Linux controls, limits, prioritizes, and monitors system resources using control groups (cgroups), providing the foundation for containers, resource isolation, and workload management.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 410 — Why cgroups Exist | Understand why Linux introduced control groups for resource management.  📋 Planned |
| Chapter 411 — cgroup History | Explore the evolution of Linux control groups.  📋 Planned |
| Chapter 412 — cgroup v1 | Learn the original cgroup architecture.  📋 Planned |
| Chapter 413 — Problems with cgroup v1 | Understand the limitations that led to a redesign.  📋 Planned |
| Chapter 414 — cgroup v2 | Explore the unified cgroup hierarchy.  📋 Planned |
| Chapter 415 — Unified Hierarchy | Learn the design principles behind the unified hierarchy.  📋 Planned |
| Chapter 416 — cgroup Filesystem | Understand how cgroups are exposed through the virtual filesystem.  📋 Planned |
| Chapter 417 — Controllers | Explore resource controllers available within cgroups.  📋 Planned |
| Chapter 418 — CPU Controller | Learn CPU resource allocation and scheduling control.  📋 Planned |
| Chapter 419 — Memory Controller | Understand memory accounting and limitation mechanisms.  📋 Planned |
| Chapter 420 — I/O Controller | Explore storage bandwidth and I/O resource control.  📋 Planned |
| Chapter 421 — PID Controller | Learn how Linux limits process creation.  📋 Planned |
| Chapter 422 — cpuset Controller | Understand CPU and memory affinity management.  📋 Planned |
| Chapter 423 — Resource Accounting | Learn how Linux measures resource consumption.  📋 Planned |
| Chapter 424 — cgroup Delegation | Understand delegation models for containers and services.  📋 Planned |
| Chapter 425 — cgroup Pressure Metrics | Explore resource pressure monitoring.  📋 Planned |
| Chapter 426 — systemd and cgroups | Learn how systemd manages cgroups automatically.  📋 Planned |
| Chapter 427 — Containers and cgroups | Understand why cgroups are fundamental to containers.  📋 Planned |
| Chapter 428 — Debugging cgroup Problems | Develop techniques for diagnosing resource management issues.  📋 Planned |

---

### Part XVII — systemd Engineering

**Purpose**

Develop a comprehensive understanding of systemd as Linux's service manager, initialization system, dependency manager, resource controller, and operating system orchestration framework.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 429 — The Init Problem | Understand why traditional init systems became insufficient.  📋 Planned |
| Chapter 430 — SysV Init | Explore the architecture of the classic UNIX initialization system.  📋 Planned |
| Chapter 431 — Upstart | Learn the motivation and design behind Upstart.  📋 Planned |
| Chapter 432 — Why systemd Was Created | Understand the engineering goals that led to systemd.  📋 Planned |
| Chapter 433 — systemd Architecture | Explore the overall architecture of systemd.  📋 Planned |
| Chapter 434 — systemd as PID 1 | Learn the responsibilities of systemd as the first userspace process.  📋 Planned |
| Chapter 435 — The systemd Manager | Understand how systemd manages system state.  📋 Planned |
| Chapter 436 — Unit Architecture | Learn the design of systemd unit files.  📋 Planned |
| Chapter 437 — Service Units | Understand service management using unit files.  📋 Planned |
| Chapter 438 — Target Units | Learn how targets organize system startup.  📋 Planned |
| Chapter 439 — Socket Units | Explore socket activation concepts.  📋 Planned |
| Chapter 440 — Timer Units | Understand timer-based service execution.  📋 Planned |
| Chapter 441 — Path Units | Learn event-driven service activation through filesystem monitoring.  📋 Planned |
| Chapter 442 — Mount Units | Understand filesystem mount management.  📋 Planned |
| Chapter 443 — Automount Units | Explore automatic mount activation.  📋 Planned |
| Chapter 444 — Swap Units | Learn swap device management with systemd.  📋 Planned |
| Chapter 445 — Device Units | Understand hardware device integration.  📋 Planned |
| Chapter 446 — Scope Units | Learn how externally created processes are managed.  📋 Planned |
| Chapter 447 — Slice Units | Understand hierarchical resource allocation.  📋 Planned |
| Chapter 448 — Unit Dependencies | Learn dependency relationships between units.  📋 Planned |
| Chapter 449 — Unit Ordering | Understand startup and shutdown ordering.  📋 Planned |
| Chapter 450 — Wants vs Requires | Distinguish optional and mandatory dependencies.  📋 Planned |
| Chapter 451 — Before and After | Learn ordering directives for service execution.  📋 Planned |
| Chapter 452 — Service Types | Explore different service execution models.  📋 Planned |
| Chapter 453 — Restart Policies | Understand automatic service recovery mechanisms.  📋 Planned |
| Chapter 454 — systemd Watchdogs | Learn service health monitoring.  📋 Planned |
| Chapter 455 — Resource Control | Explore resource limits managed by systemd.  📋 Planned |
| Chapter 456 — systemd and cgroup v2 | Understand the integration of systemd with cgroup v2.  📋 Planned |
| Chapter 457 — systemd Sandboxing | Learn application isolation techniques.  📋 Planned |
| Chapter 458 — systemd Credentials | Explore secure credential management.  📋 Planned |
| Chapter 459 — User Services | Understand per-user service management.  📋 Planned |
| Chapter 460 — Transient Units | Learn dynamically generated unit management.  📋 Planned |
| Chapter 461 — Template Units | Explore reusable service templates.  📋 Planned |
| Chapter 462 — Drop-In Configuration | Understand configuration overrides.  📋 Planned |
| Chapter 463 — Presets | Learn standardized service enablement policies.  📋 Planned |
| Chapter 464 — systemd Generators | Explore runtime unit generation.  📋 Planned |
| Chapter 465 — systemctl Internals and Usage | Master the primary administration interface.  📋 Planned |
| Chapter 466 — systemd-run | Learn transient service execution.  📋 Planned |
| Chapter 467 — systemd-analyze | Analyze startup performance and dependencies.  📋 Planned |
| Chapter 468 — Boot Critical Chains | Understand boot performance analysis.  📋 Planned |
| Chapter 469 — systemd-networkd | Explore integrated network configuration.  📋 Planned |
| Chapter 470 — systemd-resolved | Learn modern DNS resolution management.  📋 Planned |
| Chapter 471 — systemd-timesyncd | Understand time synchronization services.  📋 Planned |
| Chapter 472 — systemd-homed Context | Explore modern user account management.  📋 Planned |
| Chapter 473 — systemd-sysext | Learn system extension architecture.  📋 Planned |
| Chapter 474 — Portable Services | Understand portable service deployment.  📋 Planned |
| Chapter 475 — Unified Kernel Images and systemd | Explore UKI integration with systemd.  📋 Planned |
| Chapter 476 — Debugging systemd | Develop systematic debugging techniques.  📋 Planned |
| Chapter 477 — Designing Production systemd Services | Build reliable and maintainable production-grade services.  📋 Planned |

### Part XVIII — Linux Logging

**Purpose**

Understand how Linux records system activity, kernel events, service logs, and security information while building the knowledge required to analyze incidents, troubleshoot failures, and maintain reliable production systems.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 478 — Why Systems Need Logs | Understand the importance of logging for observability, troubleshooting, and security.  📋 Planned |
| Chapter 479 — Kernel Logging | Learn how the Linux kernel generates diagnostic information.  📋 Planned |
| Chapter 480 — printk | Explore the kernel's primary logging mechanism.  📋 Planned |
| Chapter 481 — Kernel Ring Buffer | Understand how kernel messages are temporarily stored.  📋 Planned |
| Chapter 482 — dmesg | Learn how to inspect kernel boot and runtime messages.  📋 Planned |
| Chapter 483 — Syslog History | Explore the evolution of system logging on UNIX and Linux.  📋 Planned |
| Chapter 484 — Syslog Protocol Concepts | Understand the principles behind standardized logging protocols.  📋 Planned |
| Chapter 485 — rsyslog | Learn the architecture and capabilities of rsyslog.  📋 Planned |
| Chapter 486 — syslog-ng Context | Explore the design and use cases of syslog-ng.  📋 Planned |
| Chapter 487 — systemd-journald | Understand the modern logging system integrated with systemd.  📋 Planned |
| Chapter 488 — Journal Architecture | Learn how the systemd journal stores and organizes log data.  📋 Planned |
| Chapter 489 — Journal Storage | Understand volatile and persistent journal storage.  📋 Planned |
| Chapter 490 — Structured Journal Fields | Learn how structured metadata improves log analysis.  📋 Planned |
| Chapter 491 — journalctl | Master querying and filtering journal entries.  📋 Planned |
| Chapter 492 — Journal Filtering | Explore advanced filtering techniques for efficient log analysis.  📋 Planned |
| Chapter 493 — Persistent Journals | Understand persistent logging across system reboots.  📋 Planned |
| Chapter 494 — Journal Forwarding | Learn how journal data is forwarded to external logging systems.  📋 Planned |
| Chapter 495 — Log Rotation | Understand log lifecycle management.  📋 Planned |
| Chapter 496 — logrotate | Learn automated log rotation and retention policies.  📋 Planned |
| Chapter 497 — Remote Logging | Explore centralized logging architectures.  📋 Planned |
| Chapter 498 — Audit Logs | Understand security auditing and compliance logging.  📋 Planned |
| Chapter 499 — Boot Logs | Learn how Linux records the boot sequence.  📋 Planned |
| Chapter 500 — Service Logs | Understand logging generated by system services.  📋 Planned |
| Chapter 501 — Logs as Incident Evidence | Develop techniques for using logs during troubleshooting and forensic investigations.  📋 Planned |

---

## Volume IV Glossary

**Chapter 502 — Volume IV Glossary**

A concise reference covering Linux memory management, namespaces, control groups, systemd architecture, service management, kernel logging, journal management, and production logging concepts.

---

### Volume IV Summary

Volume IV introduces the core technologies that power modern Linux systems beyond the fundamentals. Readers gain a comprehensive understanding of Linux memory management, workload isolation using namespaces and cgroups, service orchestration through systemd, and enterprise-grade logging infrastructure. Together, these topics establish the practical foundation for container technologies, virtualization, security, networking, and advanced Linux engineering explored throughout the remaining volumes.

---

## Volume V — Intermediate

**Learning Level:** Intermediate

**Theme**

Linux Software and Package Engineering → Linux Identity and Access

**Objective**

Develop a comprehensive understanding of software lifecycle management, Linux networking, remote administration, shell automation, and identity management. By completing this volume, readers will understand how Linux manages software, communicates across networks, automates administration, and secures user identities in production environments.

---

### Part XIX — Linux Software and Package Engineering

**Purpose**

Understand how Linux distributes, installs, builds, verifies, and secures software while exploring package managers, repositories, dependency resolution, build systems, and modern software supply-chain security.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 503 — Why Package Managers Exist | Understand why Linux relies on package management systems.  📋 Planned |
| Chapter 504 — Package Architecture | Learn the structure of Linux software packages.  📋 Planned |
| Chapter 505 — Binary Packages | Explore precompiled software distribution.  📋 Planned |
| Chapter 506 — Source Packages | Understand source-based software packaging.  📋 Planned |
| Chapter 507 — Package Metadata | Learn how packages describe their contents and dependencies.  📋 Planned |
| Chapter 508 — Dependency Resolution | Understand automatic dependency management.  📋 Planned |
| Chapter 509 — Software Repositories | Explore centralized software distribution systems.  📋 Planned |
| Chapter 510 — Repository Metadata | Learn how repositories organize package information.  📋 Planned |
| Chapter 511 — Package Signing | Understand package authenticity verification.  📋 Planned |
| Chapter 512 — Package Trust Chains | Learn how Linux establishes software trust.  📋 Planned |
| Chapter 513 — dpkg | Explore Debian's low-level package manager.  📋 Planned |
| Chapter 514 — APT | Understand Debian package management with APT.  📋 Planned |
| Chapter 515 — RPM | Learn the architecture of RPM packages.  📋 Planned |
| Chapter 516 — DNF | Explore Fedora and RHEL package management.  📋 Planned |
| Chapter 517 — Pacman | Understand package management in Arch Linux.  📋 Planned |
| Chapter 518 — Zypper | Learn package management within the SUSE ecosystem.  📋 Planned |
| Chapter 519 — APK | Explore Alpine Linux package management.  📋 Planned |
| Chapter 520 — Portage | Understand Gentoo's source-based package manager.  📋 Planned |
| Chapter 521 — Nix Package Manager | Learn reproducible package management with Nix.  📋 Planned |
| Chapter 522 — GNU Guix Context | Explore functional package management concepts.  📋 Planned |
| Chapter 523 — Snap | Understand universal application packaging with Snap.  📋 Planned |
| Chapter 524 — Flatpak | Learn desktop application distribution with Flatpak.  📋 Planned |
| Chapter 525 — AppImage | Explore portable Linux application packaging.  📋 Planned |
| Chapter 526 — Building Software from Source | Learn manual software compilation workflows.  📋 Planned |
| Chapter 527 — GNU Autotools | Understand the GNU build system.  📋 Planned |
| Chapter 528 — Make | Learn build automation using Make.  📋 Planned |
| Chapter 529 — CMake | Explore cross-platform build configuration.  📋 Planned |
| Chapter 530 — Meson | Understand modern build system design.  📋 Planned |
| Chapter 531 — pkg-config | Learn library dependency discovery.  📋 Planned |
| Chapter 532 — ldconfig | Understand shared library configuration.  📋 Planned |
| Chapter 533 — Reproducible Builds | Explore deterministic software build techniques.  📋 Planned |
| Chapter 534 — Software Bills of Materials | Learn software component inventory management.  📋 Planned |
| Chapter 535 — Linux Software Supply-Chain Security | Understand modern software supply-chain protection strategies.  📋 Planned |

---

### Part XX — Linux Networking

**Purpose**

Build a strong understanding of Linux networking by exploring the kernel networking stack, routing, interfaces, firewalls, traffic control, diagnostics, and production troubleshooting techniques.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 536 — Linux Network Stack Architecture | Understand the layered architecture of Linux networking.  📋 Planned |
| Chapter 537 — Network Devices | Learn how Linux represents network hardware.  📋 Planned |
| Chapter 538 — iproute2 | Master Linux network administration using iproute2.  📋 Planned |
| Chapter 539 — Linux Network Interfaces | Understand network interface configuration and management.  📋 Planned |
| Chapter 540 — IP Address Management | Learn IPv4 and IPv6 address management.  📋 Planned |
| Chapter 541 — Routing | Explore packet routing fundamentals.  📋 Planned |
| Chapter 542 — Linux Routing Tables | Understand Linux routing table management.  📋 Planned |
| Chapter 543 — Policy Routing | Learn advanced routing techniques.  📋 Planned |
| Chapter 544 — ARP | Understand address resolution in IPv4 networks.  📋 Planned |
| Chapter 545 — IPv6 Neighbor Discovery | Explore neighbor discovery in IPv6.  📋 Planned |
| Chapter 546 — Neighbor Tables | Learn neighbor cache management.  📋 Planned |
| Chapter 547 — Network Namespaces | Understand isolated networking environments.  📋 Planned |
| Chapter 548 — veth Pairs | Learn virtual Ethernet connectivity.  📋 Planned |
| Chapter 549 — Linux Bridges | Explore Layer 2 software switching.  📋 Planned |
| Chapter 550 — Bonding | Understand network redundancy and aggregation.  📋 Planned |
| Chapter 551 — VLANs | Learn virtual LAN implementation in Linux.  📋 Planned |
| Chapter 552 — VXLAN | Explore overlay networking technologies.  📋 Planned |
| Chapter 553 — TUN and TAP | Understand virtual networking interfaces.  📋 Planned |
| Chapter 554 — WireGuard | Learn modern VPN architecture.  📋 Planned |
| Chapter 555 — Multipath TCP | Explore resilient multi-path network communication.  📋 Planned |
| Chapter 556 — Netlink Networking | Understand kernel-to-userspace networking communication.  📋 Planned |
| Chapter 557 — Linux DNS Resolution | Learn Linux name resolution architecture.  📋 Planned |
| Chapter 558 — /etc/resolv.conf | Understand DNS resolver configuration.  📋 Planned |
| Chapter 559 — NSS and Name Resolution | Explore the Name Service Switch framework.  📋 Planned |
| Chapter 560 — NetworkManager | Learn desktop and enterprise network management.  📋 Planned |
| Chapter 561 — systemd-networkd | Understand server-oriented network configuration.  📋 Planned |
| Chapter 562 — Netfilter Architecture | Explore the Linux packet filtering framework.  📋 Planned |
| Chapter 563 — iptables History | Understand the evolution of Linux firewalls.  📋 Planned |
| Chapter 564 — nftables | Learn the modern Linux firewall framework.  📋 Planned |
| Chapter 565 — Connection Tracking | Explore stateful packet inspection.  📋 Planned |
| Chapter 566 — NAT on Linux | Understand network address translation.  📋 Planned |
| Chapter 567 — Linux Traffic Control | Learn bandwidth and traffic management.  📋 Planned |
| Chapter 568 — Queueing Disciplines | Explore Linux packet scheduling algorithms.  📋 Planned |
| Chapter 569 — Traffic Shaping | Understand network traffic optimization.  📋 Planned |
| Chapter 570 — Socket Inspection | Learn techniques for inspecting network sockets.  📋 Planned |
| Chapter 571 — Packet Capture | Explore network packet analysis fundamentals.  📋 Planned |
| Chapter 572 — tcpdump | Master packet capture using tcpdump.  📋 Planned |
| Chapter 573 — Linux Network Troubleshooting | Develop systematic network troubleshooting skills.  📋 Planned |
| Chapter 574 — Diagnosing DNS Failures | Learn practical DNS debugging techniques.  📋 Planned |
| Chapter 575 — Diagnosing Routing Failures | Understand routing problem diagnosis.  📋 Planned |
| Chapter 576 — Diagnosing Packet Loss | Explore methods for identifying packet loss causes.  📋 Planned |

### Part XXI — SSH and Remote Linux

**Purpose**

Understand secure remote administration in Linux by exploring the SSH protocol, authentication methods, encrypted communication, remote access architectures, tunneling, and production-grade SSH security practices.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 577 — Remote Administration Before SSH | Explore how systems were administered before SSH became the standard.  📋 Planned |
| Chapter 578 — SSH Architecture | Understand the architecture and components of the Secure Shell protocol.  📋 Planned |
| Chapter 579 — SSH Transport | Learn how SSH establishes encrypted communication channels.  📋 Planned |
| Chapter 580 — Host Keys | Understand server identity verification using host keys.  📋 Planned |
| Chapter 581 — SSH User Authentication | Explore the authentication mechanisms supported by SSH.  📋 Planned |
| Chapter 582 — Password Authentication | Learn traditional password-based authentication.  📋 Planned |
| Chapter 583 — Public-Key Authentication | Understand secure authentication using asymmetric cryptography.  📋 Planned |
| Chapter 584 — SSH Key Algorithms | Compare supported public-key algorithms and their security properties.  📋 Planned |
| Chapter 585 — ssh-agent | Learn secure key management using ssh-agent.  📋 Planned |
| Chapter 586 — SSH Certificates | Explore certificate-based authentication for large infrastructures.  📋 Planned |
| Chapter 587 — SSH Configuration | Understand client and server configuration options.  📋 Planned |
| Chapter 588 — Port Forwarding | Learn encrypted network tunneling through SSH.  📋 Planned |
| Chapter 589 — Local Forwarding | Explore forwarding local services through secure tunnels.  📋 Planned |
| Chapter 590 — Remote Forwarding | Understand exposing remote services securely.  📋 Planned |
| Chapter 591 — Dynamic Forwarding | Learn SOCKS proxy creation with SSH.  📋 Planned |
| Chapter 592 — ProxyJump | Explore multi-hop SSH connections.  📋 Planned |
| Chapter 593 — SSH Multiplexing | Improve efficiency through connection reuse.  📋 Planned |
| Chapter 594 — SFTP | Learn secure file transfer using the SSH protocol.  📋 Planned |
| Chapter 595 — SCP Evolution | Understand the evolution and modern implementation of SCP.  📋 Planned |
| Chapter 596 — SSH Hardening | Apply security best practices to production SSH deployments.  📋 Planned |
| Chapter 597 — Bastion Hosts | Understand secure jump servers for infrastructure access.  📋 Planned |
| Chapter 598 — Diagnosing SSH Failures | Develop systematic troubleshooting techniques for SSH connectivity issues.  📋 Planned |

---

### Part XXII — Bash and Shell Programming

**Purpose**

Develop practical shell scripting skills by learning Bash programming, automation techniques, defensive scripting practices, task scheduling, and production-quality Linux automation.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 599 — The Shell as a Programming Language | Understand why shells are powerful programming environments.  📋 Planned |
| Chapter 600 — Bash Execution Model | Learn how Bash interprets and executes scripts.  📋 Planned |
| Chapter 601 — Variables | Understand variable declaration and usage in Bash.  📋 Planned |
| Chapter 602 — Shell Parameters | Learn parameter expansion and manipulation.  📋 Planned |
| Chapter 603 — Arrays | Explore indexed and associative arrays in Bash.  📋 Planned |
| Chapter 604 — Functions | Learn modular script development using functions.  📋 Planned |
| Chapter 605 — Conditional Expressions | Understand decision-making constructs.  📋 Planned |
| Chapter 606 — Loops | Explore iterative programming in shell scripts.  📋 Planned |
| Chapter 607 — Shell Arithmetic | Learn integer arithmetic within Bash.  📋 Planned |
| Chapter 608 — Expansion in Scripts | Understand expansion behavior during script execution.  📋 Planned |
| Chapter 609 — Subshells | Explore process isolation using subshells.  📋 Planned |
| Chapter 610 — Pipelines in Scripts | Learn pipeline construction for automation workflows.  📋 Planned |
| Chapter 611 — Exit Status Design | Understand reliable error handling using exit codes.  📋 Planned |
| Chapter 612 — Traps | Learn cleanup and signal interception techniques.  📋 Planned |
| Chapter 613 — Signal Handling | Explore signal processing inside Bash scripts.  📋 Planned |
| Chapter 614 — set -e | Understand automatic script termination on failures.  📋 Planned |
| Chapter 615 — set -u | Learn protection against undefined variables.  📋 Planned |
| Chapter 616 — pipefail | Improve pipeline reliability and error detection.  📋 Planned |
| Chapter 617 — Defensive Bash Programming | Apply best practices for robust scripting.  📋 Planned |
| Chapter 618 — Parsing Command-Line Arguments | Learn flexible argument processing techniques.  📋 Planned |
| Chapter 619 — Script Logging | Implement effective logging within scripts.  📋 Planned |
| Chapter 620 — Temporary Files | Manage temporary resources safely.  📋 Planned |
| Chapter 621 — Script Locking | Prevent race conditions in concurrent script execution.  📋 Planned |
| Chapter 622 — Concurrent Shell Tasks | Learn parallel execution techniques.  📋 Planned |
| Chapter 623 — Testing Shell Scripts | Understand strategies for validating Bash scripts.  📋 Planned |
| Chapter 624 — ShellCheck | Improve script quality using static analysis.  📋 Planned |
| Chapter 625 — bats | Learn automated Bash testing using Bats.  📋 Planned |
| Chapter 626 — cron | Understand scheduled task execution using cron.  📋 Planned |
| Chapter 627 — at | Learn one-time job scheduling.  📋 Planned |
| Chapter 628 — systemd Timers | Explore modern timer-based automation.  📋 Planned |
| Chapter 629 — Production Linux Automation | Combine shell scripting techniques into production-ready automation workflows.  📋 Planned |

### Part XXIII — Linux Identity and Access

**Purpose**

Understand Linux identity management, authentication, authorization, privilege delegation, and enterprise identity integration to securely manage users, groups, services, and access control across Linux systems.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 630 — Linux Identity Model | Understand how Linux represents identities throughout the operating system.  📋 Planned |
| Chapter 631 — User IDs | Learn the purpose and management of User IDs (UIDs).  📋 Planned |
| Chapter 632 — Group IDs | Understand how Group IDs (GIDs) organize user permissions.  📋 Planned |
| Chapter 633 — /etc/passwd | Explore the structure and role of the passwd database.  📋 Planned |
| Chapter 634 — /etc/shadow | Learn secure password storage using the shadow database.  📋 Planned |
| Chapter 635 — /etc/group | Understand Linux group definitions and membership.  📋 Planned |
| Chapter 636 — Name Service Switch | Learn how NSS resolves users, groups, and other identity information.  📋 Planned |
| Chapter 637 — PAM Architecture | Understand the modular architecture of Pluggable Authentication Modules.  📋 Planned |
| Chapter 638 — PAM Modules | Explore authentication modules and their responsibilities.  📋 Planned |
| Chapter 639 — Password Policies | Learn how Linux enforces secure password policies.  📋 Planned |
| Chapter 640 — User Management | Understand user account creation, modification, and maintenance.  📋 Planned |
| Chapter 641 — Group Management | Learn group administration and membership management.  📋 Planned |
| Chapter 642 — sudo | Explore privilege delegation using sudo.  📋 Planned |
| Chapter 643 — sudoers | Learn how sudo policies are configured securely.  📋 Planned |
| Chapter 644 — Linux Capabilities | Understand capability-based privilege separation.  📋 Planned |
| Chapter 645 — Access Control Lists | Explore fine-grained filesystem permissions using POSIX ACLs.  📋 Planned |
| Chapter 646 — Linux Keyrings | Learn secure credential storage within the kernel.  📋 Planned |
| Chapter 647 — Service Accounts | Understand dedicated accounts used by system services.  📋 Planned |
| Chapter 648 — LDAP Context | Explore centralized directory services with LDAP.  📋 Planned |
| Chapter 649 — SSSD | Learn identity integration using the System Security Services Daemon.  📋 Planned |
| Chapter 650 — Kerberos Context | Understand Kerberos-based authentication in enterprise environments.  📋 Planned |
| Chapter 651 — Diagnosing Identity Failures | Develop practical techniques for troubleshooting authentication and authorization issues.  📋 Planned |

---

## Volume V Glossary

**Chapter 652 — Volume V Glossary**

A concise reference covering Linux package management, software repositories, dependency resolution, networking architecture, routing, SSH, shell scripting, automation, authentication, authorization, identity services, and enterprise access management.

---

### Volume V Summary

Volume V expands Linux engineering into software lifecycle management, production networking, secure remote administration, shell automation, and enterprise identity management. Readers develop practical skills for managing software packages, administering networked Linux systems, automating operational workflows, securing remote access, and implementing robust authentication and authorization mechanisms. Together, Volumes IV and V complete the **Intermediate** learning path and prepare readers for the Advanced engineering topics covered in subsequent volumes.

---

## Continue Reading

Continue with **Markdown Part 3**, beginning with **Volume VI — Advanced: Linux Security Architecture TO Linux Observability**.
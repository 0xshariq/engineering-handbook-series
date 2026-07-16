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

| Chapter | Purpose |
|---------|---------|
| Chapter 363 — Linux Memory Architecture | Understand the overall architecture of memory management in Linux. |
| Chapter 364 — Physical Memory Discovery | Learn how Linux discovers physical memory during system startup. |
| Chapter 365 — Memory Zones | Understand the purpose of memory zones within the kernel. |
| Chapter 366 — NUMA | Explore Non-Uniform Memory Access and its impact on performance. |
| Chapter 367 — Pages | Learn the fundamental memory unit used by Linux. |
| Chapter 368 — Folios | Understand the modern folio abstraction introduced for memory management. |
| Chapter 369 — Buddy Allocator | Explore Linux's primary physical memory allocator. |
| Chapter 370 — SLAB History | Understand the evolution of Linux slab allocation. |
| Chapter 371 — SLUB Allocator | Learn the architecture of the modern SLUB allocator. |
| Chapter 372 — Kernel Memory Allocation | Understand dynamic memory allocation inside the kernel. |
| Chapter 373 — User-Space Virtual Memory | Learn how Linux provides virtual memory to applications. |
| Chapter 374 — Anonymous Memory | Explore anonymous memory allocation and usage. |
| Chapter 375 — File-Backed Memory | Understand memory backed by filesystem objects. |
| Chapter 376 — Page Cache | Learn how the page cache improves filesystem performance. |
| Chapter 377 — mmap | Understand memory-mapped file access and shared memory. |
| Chapter 378 — Copy-on-Write | Explore copy-on-write memory optimization. |
| Chapter 379 — Memory Reclaim | Learn how Linux recovers memory under pressure. |
| Chapter 380 — LRU Concepts | Understand least recently used memory management strategies. |
| Chapter 381 — Swap and Reclaim | Explore swapping and page reclamation mechanisms. |
| Chapter 382 — Memory Overcommit | Learn Linux memory overcommit policies. |
| Chapter 383 — OOM Killer | Understand out-of-memory detection and recovery. |
| Chapter 384 — HugeTLB Pages | Explore explicit huge page management. |
| Chapter 385 — Transparent Huge Pages | Learn automatic huge page optimization. |
| Chapter 386 — Memory Compaction | Understand memory defragmentation techniques. |
| Chapter 387 — Memory Pressure Stall Information | Learn how Linux measures memory pressure. |
| Chapter 388 — Memory cgroups | Understand memory isolation using cgroups. |
| Chapter 389 — NUMA Memory Policy | Explore NUMA-aware memory allocation strategies. |
| Chapter 390 — Memory Hotplug | Learn dynamic memory addition and removal. |
| Chapter 391 — DAMON | Understand Data Access MONitor for workload-aware optimization. |
| Chapter 392 — Diagnosing Linux Memory Problems | Develop practical techniques for troubleshooting memory-related issues. |

---

### Part XV — Linux Namespaces

**Purpose**

Understand the kernel isolation mechanisms that form the foundation of Linux containers by exploring namespace architecture, resource isolation, and secure process separation.

| Chapter | Purpose |
|---------|---------|
| Chapter 393 — The Isolation Problem | Understand why operating systems require resource isolation. |
| Chapter 394 — Namespace History | Explore the evolution of Linux namespaces. |
| Chapter 395 — Namespace Kernel Model | Learn the kernel architecture behind namespaces. |
| Chapter 396 — Mount Namespaces | Understand filesystem isolation. |
| Chapter 397 — PID Namespaces | Learn process identifier isolation. |
| Chapter 398 — Network Namespaces | Explore isolated network stacks. |
| Chapter 399 — UTS Namespaces | Understand hostname and domain isolation. |
| Chapter 400 — IPC Namespaces | Learn inter-process communication isolation. |
| Chapter 401 — User Namespaces | Explore unprivileged namespace capabilities. |
| Chapter 402 — Cgroup Namespaces | Understand cgroup namespace virtualization. |
| Chapter 403 — Time Namespaces | Learn Linux time virtualization. |
| Chapter 404 — clone() and Namespaces | Understand namespace creation using clone(). |
| Chapter 405 — unshare() | Learn namespace separation from existing processes. |
| Chapter 406 — setns() | Explore joining existing namespaces. |
| Chapter 407 — Inspecting Namespaces | Learn techniques for namespace inspection. |
| Chapter 408 — Namespace Security Boundaries | Understand security considerations for namespace isolation. |
| Chapter 409 — Building an Isolated Process Environment | Combine namespaces to create isolated execution environments. |

### Part XVI — Linux Control Groups

**Purpose**

Understand how Linux controls, limits, prioritizes, and monitors system resources using control groups (cgroups), providing the foundation for containers, resource isolation, and workload management.

| Chapter | Purpose |
|---------|---------|
| Chapter 410 — Why cgroups Exist | Understand why Linux introduced control groups for resource management. |
| Chapter 411 — cgroup History | Explore the evolution of Linux control groups. |
| Chapter 412 — cgroup v1 | Learn the original cgroup architecture. |
| Chapter 413 — Problems with cgroup v1 | Understand the limitations that led to a redesign. |
| Chapter 414 — cgroup v2 | Explore the unified cgroup hierarchy. |
| Chapter 415 — Unified Hierarchy | Learn the design principles behind the unified hierarchy. |
| Chapter 416 — cgroup Filesystem | Understand how cgroups are exposed through the virtual filesystem. |
| Chapter 417 — Controllers | Explore resource controllers available within cgroups. |
| Chapter 418 — CPU Controller | Learn CPU resource allocation and scheduling control. |
| Chapter 419 — Memory Controller | Understand memory accounting and limitation mechanisms. |
| Chapter 420 — I/O Controller | Explore storage bandwidth and I/O resource control. |
| Chapter 421 — PID Controller | Learn how Linux limits process creation. |
| Chapter 422 — cpuset Controller | Understand CPU and memory affinity management. |
| Chapter 423 — Resource Accounting | Learn how Linux measures resource consumption. |
| Chapter 424 — cgroup Delegation | Understand delegation models for containers and services. |
| Chapter 425 — cgroup Pressure Metrics | Explore resource pressure monitoring. |
| Chapter 426 — systemd and cgroups | Learn how systemd manages cgroups automatically. |
| Chapter 427 — Containers and cgroups | Understand why cgroups are fundamental to containers. |
| Chapter 428 — Debugging cgroup Problems | Develop techniques for diagnosing resource management issues. |

---

### Part XVII — systemd Engineering

**Purpose**

Develop a comprehensive understanding of systemd as Linux's service manager, initialization system, dependency manager, resource controller, and operating system orchestration framework.

| Chapter | Purpose |
|---------|---------|
| Chapter 429 — The Init Problem | Understand why traditional init systems became insufficient. |
| Chapter 430 — SysV Init | Explore the architecture of the classic UNIX initialization system. |
| Chapter 431 — Upstart | Learn the motivation and design behind Upstart. |
| Chapter 432 — Why systemd Was Created | Understand the engineering goals that led to systemd. |
| Chapter 433 — systemd Architecture | Explore the overall architecture of systemd. |
| Chapter 434 — systemd as PID 1 | Learn the responsibilities of systemd as the first userspace process. |
| Chapter 435 — The systemd Manager | Understand how systemd manages system state. |
| Chapter 436 — Unit Architecture | Learn the design of systemd unit files. |
| Chapter 437 — Service Units | Understand service management using unit files. |
| Chapter 438 — Target Units | Learn how targets organize system startup. |
| Chapter 439 — Socket Units | Explore socket activation concepts. |
| Chapter 440 — Timer Units | Understand timer-based service execution. |
| Chapter 441 — Path Units | Learn event-driven service activation through filesystem monitoring. |
| Chapter 442 — Mount Units | Understand filesystem mount management. |
| Chapter 443 — Automount Units | Explore automatic mount activation. |
| Chapter 444 — Swap Units | Learn swap device management with systemd. |
| Chapter 445 — Device Units | Understand hardware device integration. |
| Chapter 446 — Scope Units | Learn how externally created processes are managed. |
| Chapter 447 — Slice Units | Understand hierarchical resource allocation. |
| Chapter 448 — Unit Dependencies | Learn dependency relationships between units. |
| Chapter 449 — Unit Ordering | Understand startup and shutdown ordering. |
| Chapter 450 — Wants vs Requires | Distinguish optional and mandatory dependencies. |
| Chapter 451 — Before and After | Learn ordering directives for service execution. |
| Chapter 452 — Service Types | Explore different service execution models. |
| Chapter 453 — Restart Policies | Understand automatic service recovery mechanisms. |
| Chapter 454 — systemd Watchdogs | Learn service health monitoring. |
| Chapter 455 — Resource Control | Explore resource limits managed by systemd. |
| Chapter 456 — systemd and cgroup v2 | Understand the integration of systemd with cgroup v2. |
| Chapter 457 — systemd Sandboxing | Learn application isolation techniques. |
| Chapter 458 — systemd Credentials | Explore secure credential management. |
| Chapter 459 — User Services | Understand per-user service management. |
| Chapter 460 — Transient Units | Learn dynamically generated unit management. |
| Chapter 461 — Template Units | Explore reusable service templates. |
| Chapter 462 — Drop-In Configuration | Understand configuration overrides. |
| Chapter 463 — Presets | Learn standardized service enablement policies. |
| Chapter 464 — systemd Generators | Explore runtime unit generation. |
| Chapter 465 — systemctl Internals and Usage | Master the primary administration interface. |
| Chapter 466 — systemd-run | Learn transient service execution. |
| Chapter 467 — systemd-analyze | Analyze startup performance and dependencies. |
| Chapter 468 — Boot Critical Chains | Understand boot performance analysis. |
| Chapter 469 — systemd-networkd | Explore integrated network configuration. |
| Chapter 470 — systemd-resolved | Learn modern DNS resolution management. |
| Chapter 471 — systemd-timesyncd | Understand time synchronization services. |
| Chapter 472 — systemd-homed Context | Explore modern user account management. |
| Chapter 473 — systemd-sysext | Learn system extension architecture. |
| Chapter 474 — Portable Services | Understand portable service deployment. |
| Chapter 475 — Unified Kernel Images and systemd | Explore UKI integration with systemd. |
| Chapter 476 — Debugging systemd | Develop systematic debugging techniques. |
| Chapter 477 — Designing Production systemd Services | Build reliable and maintainable production-grade services. |

### Part XVIII — Linux Logging

**Purpose**

Understand how Linux records system activity, kernel events, service logs, and security information while building the knowledge required to analyze incidents, troubleshoot failures, and maintain reliable production systems.

| Chapter | Purpose |
|---------|---------|
| Chapter 478 — Why Systems Need Logs | Understand the importance of logging for observability, troubleshooting, and security. |
| Chapter 479 — Kernel Logging | Learn how the Linux kernel generates diagnostic information. |
| Chapter 480 — printk | Explore the kernel's primary logging mechanism. |
| Chapter 481 — Kernel Ring Buffer | Understand how kernel messages are temporarily stored. |
| Chapter 482 — dmesg | Learn how to inspect kernel boot and runtime messages. |
| Chapter 483 — Syslog History | Explore the evolution of system logging on UNIX and Linux. |
| Chapter 484 — Syslog Protocol Concepts | Understand the principles behind standardized logging protocols. |
| Chapter 485 — rsyslog | Learn the architecture and capabilities of rsyslog. |
| Chapter 486 — syslog-ng Context | Explore the design and use cases of syslog-ng. |
| Chapter 487 — systemd-journald | Understand the modern logging system integrated with systemd. |
| Chapter 488 — Journal Architecture | Learn how the systemd journal stores and organizes log data. |
| Chapter 489 — Journal Storage | Understand volatile and persistent journal storage. |
| Chapter 490 — Structured Journal Fields | Learn how structured metadata improves log analysis. |
| Chapter 491 — journalctl | Master querying and filtering journal entries. |
| Chapter 492 — Journal Filtering | Explore advanced filtering techniques for efficient log analysis. |
| Chapter 493 — Persistent Journals | Understand persistent logging across system reboots. |
| Chapter 494 — Journal Forwarding | Learn how journal data is forwarded to external logging systems. |
| Chapter 495 — Log Rotation | Understand log lifecycle management. |
| Chapter 496 — logrotate | Learn automated log rotation and retention policies. |
| Chapter 497 — Remote Logging | Explore centralized logging architectures. |
| Chapter 498 — Audit Logs | Understand security auditing and compliance logging. |
| Chapter 499 — Boot Logs | Learn how Linux records the boot sequence. |
| Chapter 500 — Service Logs | Understand logging generated by system services. |
| Chapter 501 — Logs as Incident Evidence | Develop techniques for using logs during troubleshooting and forensic investigations. |

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

| Chapter | Purpose |
|---------|---------|
| Chapter 503 — Why Package Managers Exist | Understand why Linux relies on package management systems. |
| Chapter 504 — Package Architecture | Learn the structure of Linux software packages. |
| Chapter 505 — Binary Packages | Explore precompiled software distribution. |
| Chapter 506 — Source Packages | Understand source-based software packaging. |
| Chapter 507 — Package Metadata | Learn how packages describe their contents and dependencies. |
| Chapter 508 — Dependency Resolution | Understand automatic dependency management. |
| Chapter 509 — Software Repositories | Explore centralized software distribution systems. |
| Chapter 510 — Repository Metadata | Learn how repositories organize package information. |
| Chapter 511 — Package Signing | Understand package authenticity verification. |
| Chapter 512 — Package Trust Chains | Learn how Linux establishes software trust. |
| Chapter 513 — dpkg | Explore Debian's low-level package manager. |
| Chapter 514 — APT | Understand Debian package management with APT. |
| Chapter 515 — RPM | Learn the architecture of RPM packages. |
| Chapter 516 — DNF | Explore Fedora and RHEL package management. |
| Chapter 517 — Pacman | Understand package management in Arch Linux. |
| Chapter 518 — Zypper | Learn package management within the SUSE ecosystem. |
| Chapter 519 — APK | Explore Alpine Linux package management. |
| Chapter 520 — Portage | Understand Gentoo's source-based package manager. |
| Chapter 521 — Nix Package Manager | Learn reproducible package management with Nix. |
| Chapter 522 — GNU Guix Context | Explore functional package management concepts. |
| Chapter 523 — Snap | Understand universal application packaging with Snap. |
| Chapter 524 — Flatpak | Learn desktop application distribution with Flatpak. |
| Chapter 525 — AppImage | Explore portable Linux application packaging. |
| Chapter 526 — Building Software from Source | Learn manual software compilation workflows. |
| Chapter 527 — GNU Autotools | Understand the GNU build system. |
| Chapter 528 — Make | Learn build automation using Make. |
| Chapter 529 — CMake | Explore cross-platform build configuration. |
| Chapter 530 — Meson | Understand modern build system design. |
| Chapter 531 — pkg-config | Learn library dependency discovery. |
| Chapter 532 — ldconfig | Understand shared library configuration. |
| Chapter 533 — Reproducible Builds | Explore deterministic software build techniques. |
| Chapter 534 — Software Bills of Materials | Learn software component inventory management. |
| Chapter 535 — Linux Software Supply-Chain Security | Understand modern software supply-chain protection strategies. |

---

### Part XX — Linux Networking

**Purpose**

Build a strong understanding of Linux networking by exploring the kernel networking stack, routing, interfaces, firewalls, traffic control, diagnostics, and production troubleshooting techniques.

| Chapter | Purpose |
|---------|---------|
| Chapter 536 — Linux Network Stack Architecture | Understand the layered architecture of Linux networking. |
| Chapter 537 — Network Devices | Learn how Linux represents network hardware. |
| Chapter 538 — iproute2 | Master Linux network administration using iproute2. |
| Chapter 539 — Linux Network Interfaces | Understand network interface configuration and management. |
| Chapter 540 — IP Address Management | Learn IPv4 and IPv6 address management. |
| Chapter 541 — Routing | Explore packet routing fundamentals. |
| Chapter 542 — Linux Routing Tables | Understand Linux routing table management. |
| Chapter 543 — Policy Routing | Learn advanced routing techniques. |
| Chapter 544 — ARP | Understand address resolution in IPv4 networks. |
| Chapter 545 — IPv6 Neighbor Discovery | Explore neighbor discovery in IPv6. |
| Chapter 546 — Neighbor Tables | Learn neighbor cache management. |
| Chapter 547 — Network Namespaces | Understand isolated networking environments. |
| Chapter 548 — veth Pairs | Learn virtual Ethernet connectivity. |
| Chapter 549 — Linux Bridges | Explore Layer 2 software switching. |
| Chapter 550 — Bonding | Understand network redundancy and aggregation. |
| Chapter 551 — VLANs | Learn virtual LAN implementation in Linux. |
| Chapter 552 — VXLAN | Explore overlay networking technologies. |
| Chapter 553 — TUN and TAP | Understand virtual networking interfaces. |
| Chapter 554 — WireGuard | Learn modern VPN architecture. |
| Chapter 555 — Multipath TCP | Explore resilient multi-path network communication. |
| Chapter 556 — Netlink Networking | Understand kernel-to-userspace networking communication. |
| Chapter 557 — Linux DNS Resolution | Learn Linux name resolution architecture. |
| Chapter 558 — /etc/resolv.conf | Understand DNS resolver configuration. |
| Chapter 559 — NSS and Name Resolution | Explore the Name Service Switch framework. |
| Chapter 560 — NetworkManager | Learn desktop and enterprise network management. |
| Chapter 561 — systemd-networkd | Understand server-oriented network configuration. |
| Chapter 562 — Netfilter Architecture | Explore the Linux packet filtering framework. |
| Chapter 563 — iptables History | Understand the evolution of Linux firewalls. |
| Chapter 564 — nftables | Learn the modern Linux firewall framework. |
| Chapter 565 — Connection Tracking | Explore stateful packet inspection. |
| Chapter 566 — NAT on Linux | Understand network address translation. |
| Chapter 567 — Linux Traffic Control | Learn bandwidth and traffic management. |
| Chapter 568 — Queueing Disciplines | Explore Linux packet scheduling algorithms. |
| Chapter 569 — Traffic Shaping | Understand network traffic optimization. |
| Chapter 570 — Socket Inspection | Learn techniques for inspecting network sockets. |
| Chapter 571 — Packet Capture | Explore network packet analysis fundamentals. |
| Chapter 572 — tcpdump | Master packet capture using tcpdump. |
| Chapter 573 — Linux Network Troubleshooting | Develop systematic network troubleshooting skills. |
| Chapter 574 — Diagnosing DNS Failures | Learn practical DNS debugging techniques. |
| Chapter 575 — Diagnosing Routing Failures | Understand routing problem diagnosis. |
| Chapter 576 — Diagnosing Packet Loss | Explore methods for identifying packet loss causes. |

### Part XXI — SSH and Remote Linux

**Purpose**

Understand secure remote administration in Linux by exploring the SSH protocol, authentication methods, encrypted communication, remote access architectures, tunneling, and production-grade SSH security practices.

| Chapter | Purpose |
|---------|---------|
| Chapter 577 — Remote Administration Before SSH | Explore how systems were administered before SSH became the standard. |
| Chapter 578 — SSH Architecture | Understand the architecture and components of the Secure Shell protocol. |
| Chapter 579 — SSH Transport | Learn how SSH establishes encrypted communication channels. |
| Chapter 580 — Host Keys | Understand server identity verification using host keys. |
| Chapter 581 — SSH User Authentication | Explore the authentication mechanisms supported by SSH. |
| Chapter 582 — Password Authentication | Learn traditional password-based authentication. |
| Chapter 583 — Public-Key Authentication | Understand secure authentication using asymmetric cryptography. |
| Chapter 584 — SSH Key Algorithms | Compare supported public-key algorithms and their security properties. |
| Chapter 585 — ssh-agent | Learn secure key management using ssh-agent. |
| Chapter 586 — SSH Certificates | Explore certificate-based authentication for large infrastructures. |
| Chapter 587 — SSH Configuration | Understand client and server configuration options. |
| Chapter 588 — Port Forwarding | Learn encrypted network tunneling through SSH. |
| Chapter 589 — Local Forwarding | Explore forwarding local services through secure tunnels. |
| Chapter 590 — Remote Forwarding | Understand exposing remote services securely. |
| Chapter 591 — Dynamic Forwarding | Learn SOCKS proxy creation with SSH. |
| Chapter 592 — ProxyJump | Explore multi-hop SSH connections. |
| Chapter 593 — SSH Multiplexing | Improve efficiency through connection reuse. |
| Chapter 594 — SFTP | Learn secure file transfer using the SSH protocol. |
| Chapter 595 — SCP Evolution | Understand the evolution and modern implementation of SCP. |
| Chapter 596 — SSH Hardening | Apply security best practices to production SSH deployments. |
| Chapter 597 — Bastion Hosts | Understand secure jump servers for infrastructure access. |
| Chapter 598 — Diagnosing SSH Failures | Develop systematic troubleshooting techniques for SSH connectivity issues. |

---

### Part XXII — Bash and Shell Programming

**Purpose**

Develop practical shell scripting skills by learning Bash programming, automation techniques, defensive scripting practices, task scheduling, and production-quality Linux automation.

| Chapter | Purpose |
|---------|---------|
| Chapter 599 — The Shell as a Programming Language | Understand why shells are powerful programming environments. |
| Chapter 600 — Bash Execution Model | Learn how Bash interprets and executes scripts. |
| Chapter 601 — Variables | Understand variable declaration and usage in Bash. |
| Chapter 602 — Shell Parameters | Learn parameter expansion and manipulation. |
| Chapter 603 — Arrays | Explore indexed and associative arrays in Bash. |
| Chapter 604 — Functions | Learn modular script development using functions. |
| Chapter 605 — Conditional Expressions | Understand decision-making constructs. |
| Chapter 606 — Loops | Explore iterative programming in shell scripts. |
| Chapter 607 — Shell Arithmetic | Learn integer arithmetic within Bash. |
| Chapter 608 — Expansion in Scripts | Understand expansion behavior during script execution. |
| Chapter 609 — Subshells | Explore process isolation using subshells. |
| Chapter 610 — Pipelines in Scripts | Learn pipeline construction for automation workflows. |
| Chapter 611 — Exit Status Design | Understand reliable error handling using exit codes. |
| Chapter 612 — Traps | Learn cleanup and signal interception techniques. |
| Chapter 613 — Signal Handling | Explore signal processing inside Bash scripts. |
| Chapter 614 — set -e | Understand automatic script termination on failures. |
| Chapter 615 — set -u | Learn protection against undefined variables. |
| Chapter 616 — pipefail | Improve pipeline reliability and error detection. |
| Chapter 617 — Defensive Bash Programming | Apply best practices for robust scripting. |
| Chapter 618 — Parsing Command-Line Arguments | Learn flexible argument processing techniques. |
| Chapter 619 — Script Logging | Implement effective logging within scripts. |
| Chapter 620 — Temporary Files | Manage temporary resources safely. |
| Chapter 621 — Script Locking | Prevent race conditions in concurrent script execution. |
| Chapter 622 — Concurrent Shell Tasks | Learn parallel execution techniques. |
| Chapter 623 — Testing Shell Scripts | Understand strategies for validating Bash scripts. |
| Chapter 624 — ShellCheck | Improve script quality using static analysis. |
| Chapter 625 — bats | Learn automated Bash testing using Bats. |
| Chapter 626 — cron | Understand scheduled task execution using cron. |
| Chapter 627 — at | Learn one-time job scheduling. |
| Chapter 628 — systemd Timers | Explore modern timer-based automation. |
| Chapter 629 — Production Linux Automation | Combine shell scripting techniques into production-ready automation workflows. |

### Part XXIII — Linux Identity and Access

**Purpose**

Understand Linux identity management, authentication, authorization, privilege delegation, and enterprise identity integration to securely manage users, groups, services, and access control across Linux systems.

| Chapter | Purpose |
|---------|---------|
| Chapter 630 — Linux Identity Model | Understand how Linux represents identities throughout the operating system. |
| Chapter 631 — User IDs | Learn the purpose and management of User IDs (UIDs). |
| Chapter 632 — Group IDs | Understand how Group IDs (GIDs) organize user permissions. |
| Chapter 633 — /etc/passwd | Explore the structure and role of the passwd database. |
| Chapter 634 — /etc/shadow | Learn secure password storage using the shadow database. |
| Chapter 635 — /etc/group | Understand Linux group definitions and membership. |
| Chapter 636 — Name Service Switch | Learn how NSS resolves users, groups, and other identity information. |
| Chapter 637 — PAM Architecture | Understand the modular architecture of Pluggable Authentication Modules. |
| Chapter 638 — PAM Modules | Explore authentication modules and their responsibilities. |
| Chapter 639 — Password Policies | Learn how Linux enforces secure password policies. |
| Chapter 640 — User Management | Understand user account creation, modification, and maintenance. |
| Chapter 641 — Group Management | Learn group administration and membership management. |
| Chapter 642 — sudo | Explore privilege delegation using sudo. |
| Chapter 643 — sudoers | Learn how sudo policies are configured securely. |
| Chapter 644 — Linux Capabilities | Understand capability-based privilege separation. |
| Chapter 645 — Access Control Lists | Explore fine-grained filesystem permissions using POSIX ACLs. |
| Chapter 646 — Linux Keyrings | Learn secure credential storage within the kernel. |
| Chapter 647 — Service Accounts | Understand dedicated accounts used by system services. |
| Chapter 648 — LDAP Context | Explore centralized directory services with LDAP. |
| Chapter 649 — SSSD | Learn identity integration using the System Security Services Daemon. |
| Chapter 650 — Kerberos Context | Understand Kerberos-based authentication in enterprise environments. |
| Chapter 651 — Diagnosing Identity Failures | Develop practical techniques for troubleshooting authentication and authorization issues. |

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

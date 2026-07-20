# Database Engineering Handbook

> **Engineering Handbook Series**

---

## Overview

The **Database Engineering Handbook** is a comprehensive engineering reference designed to teach database systems from first principles through modern production architectures.

Rather than focusing solely on SQL or a particular database product, this handbook explains the universal concepts, internal mechanisms, and engineering decisions that power modern database systems. Readers progressively learn how data evolved from manual record keeping to relational databases, storage engines, indexing structures, transaction processing, distributed databases, cloud-native architectures, AI retrieval systems, and complete database engine implementation.

The curriculum follows a level-based progression, beginning with foundational database concepts and gradually advancing toward production-grade database internals, distributed systems, modern cloud architectures, AI-native databases, and database engine construction.

---

## Handbook Information

| Field | Value |
|--------|-------|
| **Title** | Database Engineering Handbook |
| **Subtitle** | A Complete Guide to Database Internals, Storage Engines, SQL, Transactions, Distributed Databases, Cloud-Native Systems, AI Retrieval, and Building Database Systems |
| **Edition** | Second Edition |
| **Status** | 🚧 In Development |
| **Series** | Engineering Handbook Series |
| **Discipline** | Computer Science / Database Engineering |
| **Level** | Foundation → Intermediate → Advanced → Professional → Specialist → Capstone |
| **Volumes** | 21 |
| **Total Chapters** | 1,593 |
| **Sequel Of** | Database Engineering Handbook (First Edition) |
| **Author** | Sharique Chaudhary |

---

## What You Will Learn

After completing this handbook, readers will be able to:

- Understand the complete evolution of database systems from manual data management to modern distributed databases.
- Master database architecture, storage engines, and database management system internals.
- Understand pages, records, file organization, and physical storage structures.
- Learn indexing techniques including B+ Trees, LSM Trees, learned indexes, vector indexes, and probabilistic data structures.
- Understand transaction processing, concurrency control, MVCC, serializability, logging, and crash recovery.
- Master relational theory, SQL, query semantics, schema design, query optimization, and execution engines.
- Explore distributed databases, replication, consensus, cloud-native storage, and large-scale data infrastructure.
- Understand AI-native databases, vector search, semantic retrieval, retrieval-augmented generation (RAG), and modern retrieval systems.
- Study the internal architecture of production database systems including SQLite, PostgreSQL, MySQL, RocksDB, FoundationDB, CockroachDB, TiDB, DuckDB, ClickHouse, Snowflake, BigQuery, and other modern database platforms.
- Build storage engines, query processors, transaction managers, distributed database components, and complete database systems from scratch.
- Develop the engineering intuition required to understand, optimize, and contribute to production-grade database systems.

---

## Intended Audience

This handbook is designed for:

- Computer Science students
- Software Engineers
- Backend Engineers
- Database Engineers
- Database Administrators (DBAs)
- Systems Programmers
- Storage Engine Developers
- Distributed Systems Engineers
- Cloud Infrastructure Engineers
- Site Reliability Engineers (SREs)
- Data Platform Engineers
- Performance Engineers
- AI Infrastructure Engineers
- Researchers
- Anyone interested in understanding how modern database systems work internally.

---

## Handbook Structure

The handbook is organized into **21 progressive volumes**, with each volume representing a distinct stage in the database engineering learning journey. Every volume functions as a self-contained mini-book while contributing to the complete curriculum.

The curriculum begins with the historical evolution of data management and database fundamentals before progressing through hardware, operating system interaction, storage engines, indexing, transactions, SQL, query optimization, distributed databases, cloud-native architectures, AI retrieval systems, and production database internals.

Following the Engineering Handbook philosophy of **WHY before HOW**, the handbook emphasizes engineering intuition, implementation details, architectural trade-offs, source-code analysis, production system design, and build-from-scratch projects before introducing vendor-specific technologies.

The curriculum progresses through six educational levels:

- Foundation
- Intermediate
- Advanced
- Professional
- Specialist
- Capstone

The final volumes focus on complete database engine engineering, production database architectures, distributed systems, AI-native retrieval platforms, and comprehensive capstone projects that integrate concepts from the entire handbook into real-world database systems.

---

## Volume I — Foundation: Data Before Databases to Operating System and Filesystem Interaction

**Learning Level:** Foundation

**Theme**

Study the complete evolution of data management from manual record-keeping to modern database systems while establishing the architectural, hardware, operating system, and storage foundations required to understand every modern database engine.

**Objective**

Build a strong engineering foundation by understanding why database systems evolved, how modern DBMSs are organized, how hardware influences database performance, and how operating systems interact with database engines before progressing to storage engines, indexing, transactions, query processing, and distributed databases.

---

## Part I — Data Before Databases

**Purpose**

Study the historical evolution of data management systems from manual records to modern cloud-native databases while understanding the engineering challenges, architectural breakthroughs, and technological innovations that shaped the database industry.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 1 | Why Humans Store Data | 📋 Planned |
| Chapter 2 | Ledgers, Registers, and Manual Records | 📋 Planned |
| Chapter 3 | Punched Cards and Machine-Readable Data | 📋 Planned |
| Chapter 4 | Magnetic Tape and Sequential Processing | 📋 Planned |
| Chapter 5 | The File Processing Era | 📋 Planned |
| Chapter 6 | Flat Files | 📋 Planned |
| Chapter 7 | Application-Owned Data | 📋 Planned |
| Chapter 8 | Data Redundancy | 📋 Planned |
| Chapter 9 | Update Anomalies | 📋 Planned |
| Chapter 10 | Physical Data Dependence | 📋 Planned |
| Chapter 11 | Indexed Sequential Access Methods | 📋 Planned |
| Chapter 12 | Hierarchical Databases | 📋 Planned |
| Chapter 13 | IBM IMS and Tree-Oriented Data | 📋 Planned |
| Chapter 14 | Network Databases | 📋 Planned |
| Chapter 15 | CODASYL and Navigational Data Access | 📋 Planned |
| Chapter 16 | Why Navigational Databases Became Difficult | 📋 Planned |
| Chapter 17 | Edgar F. Codd and the Relational Revolution | 📋 Planned |
| Chapter 18 | Data Independence | 📋 Planned |
| Chapter 19 | Declarative Data Access | 📋 Planned |
| Chapter 20 | System R | 📋 Planned |
| Chapter 21 | INGRES and QUEL | 📋 Planned |
| Chapter 22 | SEQUEL Becomes SQL | 📋 Planned |
| Chapter 23 | Commercial Relational Databases | 📋 Planned |
| Chapter 24 | Client-Server Database Systems | 📋 Planned |
| Chapter 25 | The Internet Changes Database Workloads | 📋 Planned |
| Chapter 26 | The NoSQL Movement | 📋 Planned |
| Chapter 27 | Cloud Databases | 📋 Planned |
| Chapter 28 | Distributed SQL | 📋 Planned |
| Chapter 29 | Serverless Databases | 📋 Planned |
| Chapter 30 | The Modern Database Landscape | 📋 Planned |

---

## Part II — Database System Foundations

**Purpose**

Study the core architecture of database management systems by understanding the responsibilities of every major subsystem, the data models supported by modern databases, deployment architectures, and the complete lifecycle of database request processing.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 31 | What Is Data? | 📋 Planned |
| Chapter 32 | What Is a Database? | 📋 Planned |
| Chapter 33 | What Is a DBMS? | 📋 Planned |
| Chapter 34 | Database vs Database Management System | 📋 Planned |
| Chapter 35 | Database Server | 📋 Planned |
| Chapter 36 | Database Engine | 📋 Planned |
| Chapter 37 | Storage Engine | 📋 Planned |
| Chapter 38 | Query Engine | 📋 Planned |
| Chapter 39 | Transaction Manager | 📋 Planned |
| Chapter 40 | Recovery Manager | 📋 Planned |
| Chapter 41 | Buffer Manager | 📋 Planned |
| Chapter 42 | Catalog and Metadata | 📋 Planned |
| Chapter 43 | Schemas | 📋 Planned |
| Chapter 44 | Relations, Rows, and Records | 📋 Planned |
| Chapter 45 | Documents | 📋 Planned |
| Chapter 46 | Key-Value Data | 📋 Planned |
| Chapter 47 | Column Families | 📋 Planned |
| Chapter 48 | Graph Data | 📋 Planned |
| Chapter 49 | Embedded Databases | 📋 Planned |
| Chapter 50 | Client-Server Databases | 📋 Planned |
| Chapter 51 | Process-per-Connection Architectures | 📋 Planned |
| Chapter 52 | Thread-per-Connection Architectures | 📋 Planned |
| Chapter 53 | Event-Driven Database Architectures | 📋 Planned |
| Chapter 54 | Shared-Everything Systems | 📋 Planned |
| Chapter 55 | Shared-Disk Systems | 📋 Planned |
| Chapter 56 | Shared-Nothing Systems | 📋 Planned |
| Chapter 57 | Database Control Planes | 📋 Planned |
| Chapter 58 | Database Data Planes | 📋 Planned |
| Chapter 59 | Anatomy of a Database Request | 📋 Planned |
| Chapter 60 | Anatomy of a Database Engine | 📋 Planned |

---

## Part III — Hardware Foundations for Database Engineers

**Purpose**

Study the hardware principles that underpin modern database systems by understanding processors, memory hierarchies, storage technologies, networking hardware, cache behavior, and system architecture. These concepts provide the engineering foundation required to design high-performance storage engines and scalable database systems.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 61 | Why Database Engineers Must Understand Hardware | 📋 Planned |
| Chapter 62 | Hardware Foundations for Database Engineers: Engineering Topic 2 | 📋 Planned |
| Chapter 63 | Hardware Foundations for Database Engineers: Engineering Topic 3 | 📋 Planned |
| Chapter 64 | Hardware Foundations for Database Engineers: Engineering Topic 4 | 📋 Planned |
| Chapter 65 | Hardware Foundations for Database Engineers: Engineering Topic 5 | 📋 Planned |
| Chapter 66 | Hardware Foundations for Database Engineers: Engineering Topic 6 | 📋 Planned |
| Chapter 67 | Hardware Foundations for Database Engineers: Engineering Topic 7 | 📋 Planned |
| Chapter 68 | Hardware Foundations for Database Engineers: Engineering Topic 8 | 📋 Planned |
| Chapter 69 | Hardware Foundations for Database Engineers: Engineering Topic 9 | 📋 Planned |
| Chapter 70 | Hardware Foundations for Database Engineers: Engineering Topic 10 | 📋 Planned |
| Chapter 71 | Hardware Foundations for Database Engineers: Engineering Topic 11 | 📋 Planned |
| Chapter 72 | Hardware Foundations for Database Engineers: Engineering Topic 12 | 📋 Planned |
| Chapter 73 | Hardware Foundations for Database Engineers: Engineering Topic 13 | 📋 Planned |
| Chapter 74 | Hardware Foundations for Database Engineers: Engineering Topic 14 | 📋 Planned |
| Chapter 75 | Hardware Foundations for Database Engineers: Engineering Topic 15 | 📋 Planned |
| Chapter 76 | Hardware Foundations for Database Engineers: Engineering Topic 16 | 📋 Planned |
| Chapter 77 | Hardware Foundations for Database Engineers: Engineering Topic 17 | 📋 Planned |
| Chapter 78 | Hardware Foundations for Database Engineers: Engineering Topic 18 | 📋 Planned |
| Chapter 79 | Hardware Foundations for Database Engineers: Engineering Topic 19 | 📋 Planned |
| Chapter 80 | Hardware Foundations for Database Engineers: Engineering Topic 20 | 📋 Planned |
| Chapter 81 | Hardware Foundations for Database Engineers: Engineering Topic 21 | 📋 Planned |
| Chapter 82 | Hardware Foundations for Database Engineers: Engineering Topic 22 | 📋 Planned |
| Chapter 83 | Hardware Foundations for Database Engineers: Engineering Topic 23 | 📋 Planned |
| Chapter 84 | Hardware Foundations for Database Engineers: Engineering Topic 24 | 📋 Planned |
| Chapter 85 | Hardware Foundations for Database Engineers: Engineering Topic 25 | 📋 Planned |
| Chapter 86 | Hardware Foundations for Database Engineers: Engineering Topic 26 | 📋 Planned |
| Chapter 87 | Hardware Foundations for Database Engineers: Engineering Topic 27 | 📋 Planned |
| Chapter 88 | Hardware Foundations for Database Engineers: Engineering Topic 28 | 📋 Planned |
| Chapter 89 | Hardware Foundations for Database Engineers: Engineering Topic 29 | 📋 Planned |
| Chapter 90 | Object Storage for Database Engineers | 📋 Planned |

---

## Part IV — Modern Database Hardware, CXL, RDMA, and Heterogeneous Compute

**Purpose**

Study the next generation of database hardware platforms and emerging computing technologies that are reshaping modern database architectures, enabling lower latency, higher throughput, memory disaggregation, hardware acceleration, and AI-ready infrastructure.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 91 | CXL Memory Expansion for Database Systems | 📋 Planned |
| Chapter 92 | Memory Pooling and Fabric-Attached Memory | 📋 Planned |
| Chapter 93 | NUMA under Disaggregated Memory | 📋 Planned |
| Chapter 94 | RDMA Verbs for Database Engineers | 📋 Planned |
| Chapter 95 | One-Sided RDMA Database Access | 📋 Planned |
| Chapter 96 | SmartNICs and Database Offload | 📋 Planned |
| Chapter 97 | DPUs in Data Infrastructure | 📋 Planned |
| Chapter 98 | GPU-Accelerated Query Processing | 📋 Planned |
| Chapter 99 | Persistent Memory Lessons and Post-Optane Design | 📋 Planned |
| Chapter 100 | Designing a Heterogeneous Database Hardware Lab | 📋 Planned |

---

## Part V — Operating System and Filesystem Interaction

**Purpose**

Study how database systems interact with operating systems, virtual memory, filesystems, storage stacks, asynchronous I/O, process scheduling, and kernel services to achieve high-performance, reliable, and scalable data management. This part establishes the systems-level knowledge required to understand modern storage engine implementation.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 101 | The Database and the Operating System | 📋 Planned |
| Chapter 102 | Operating System and Filesystem Interaction: Engineering Topic 2 | 📋 Planned |
| Chapter 103 | Operating System and Filesystem Interaction: Engineering Topic 3 | 📋 Planned |
| Chapter 104 | Operating System and Filesystem Interaction: Engineering Topic 4 | 📋 Planned |
| Chapter 105 | Operating System and Filesystem Interaction: Engineering Topic 5 | 📋 Planned |
| Chapter 106 | Operating System and Filesystem Interaction: Engineering Topic 6 | 📋 Planned |
| Chapter 107 | Operating System and Filesystem Interaction: Engineering Topic 7 | 📋 Planned |
| Chapter 108 | Operating System and Filesystem Interaction: Engineering Topic 8 | 📋 Planned |
| Chapter 109 | Operating System and Filesystem Interaction: Engineering Topic 9 | 📋 Planned |
| Chapter 110 | Operating System and Filesystem Interaction: Engineering Topic 10 | 📋 Planned |
| Chapter 111 | Operating System and Filesystem Interaction: Engineering Topic 11 | 📋 Planned |
| Chapter 112 | Operating System and Filesystem Interaction: Engineering Topic 12 | 📋 Planned |
| Chapter 113 | Operating System and Filesystem Interaction: Engineering Topic 13 | 📋 Planned |
| Chapter 114 | Operating System and Filesystem Interaction: Engineering Topic 14 | 📋 Planned |
| Chapter 115 | Operating System and Filesystem Interaction: Engineering Topic 15 | 📋 Planned |
| Chapter 116 | Operating System and Filesystem Interaction: Engineering Topic 16 | 📋 Planned |
| Chapter 117 | Operating System and Filesystem Interaction: Engineering Topic 17 | 📋 Planned |
| Chapter 118 | Operating System and Filesystem Interaction: Engineering Topic 18 | 📋 Planned |
| Chapter 119 | Operating System and Filesystem Interaction: Engineering Topic 19 | 📋 Planned |
| Chapter 120 | Operating System and Filesystem Interaction: Engineering Topic 20 | 📋 Planned |
| Chapter 121 | Operating System and Filesystem Interaction: Engineering Topic 21 | 📋 Planned |
| Chapter 122 | Operating System and Filesystem Interaction: Engineering Topic 22 | 📋 Planned |
| Chapter 123 | Operating System and Filesystem Interaction: Engineering Topic 23 | 📋 Planned |
| Chapter 124 | Choosing an I/O Strategy | 📋 Planned |

---

## Volume I Glossary

| Topic | Status |
|--------|--------|
| Chapter 125 — Volume I Glossary | 📋 Planned |

---

## Volume I Summary

The first volume establishes the engineering foundations upon which the remainder of the **Database Engineering Handbook** is built. Readers begin by studying the historical evolution of data management, from manual record-keeping and early file processing systems to relational, NoSQL, distributed, cloud-native, and serverless databases. The volume then introduces the architecture of modern database management systems, explaining the responsibilities of every major subsystem, including storage engines, query engines, transaction managers, recovery managers, buffer managers, catalogs, and deployment architectures.

Building upon this architectural foundation, the volume explores the hardware principles that influence database performance, including processor architecture, memory hierarchies, storage technologies, networking hardware, object storage, and modern heterogeneous computing platforms. Readers are then introduced to emerging technologies such as CXL, RDMA, SmartNICs, DPUs, GPU-accelerated query processing, persistent memory, and memory disaggregation, providing insight into the future of database infrastructure.

The volume concludes by examining the relationship between database systems, operating systems, and filesystems, covering process management, virtual memory, storage stacks, asynchronous I/O, and database-specific I/O strategies. Together, these topics provide the conceptual and systems-level understanding required for the advanced study of storage engines, indexing, transaction processing, query optimization, distributed databases, and database implementation throughout the remaining volumes of the handbook.

---

## Volume II — Foundation: Async I/O, io_uring, and Modern Storage Paths to Buffer Pool Engineering

**Learning Level:** Foundation

**Theme**

Study how modern database systems move data efficiently between storage devices, operating systems, and memory while understanding asynchronous I/O, physical storage organization, cloud-native storage architectures, and buffer pool engineering.

**Objective**

Build a strong understanding of modern database storage by learning asynchronous I/O, Linux io_uring, page organization, file layouts, cloud-native storage engines, and buffer pool implementation before progressing to indexing, transactions, and query processing.

---

## Part VI — Async I/O, io_uring, and Modern Storage Paths

**Purpose**

Study modern database I/O architectures by understanding Linux io_uring, asynchronous storage pipelines, kernel interactions, direct I/O, batching strategies, and high-performance storage access mechanisms used by modern database engines.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 126 | Linux io_uring Mental Model | 📋 Planned |
| Chapter 127 | Submission and Completion Queues | 📋 Planned |
| Chapter 128 | Registered Buffers and Fixed Files | 📋 Planned |
| Chapter 129 | Direct I/O with Asynchronous Engines | 📋 Planned |
| Chapter 130 | Database I/O Batching | 📋 Planned |
| Chapter 131 | Read-Ahead under Async I/O | 📋 Planned |
| Chapter 132 | Async I/O and Buffer Managers | 📋 Planned |
| Chapter 133 | Kernel Bypass Storage Context | 📋 Planned |
| Chapter 134 | Failure Semantics in Async Storage Paths | 📋 Planned |
| Chapter 135 | Building an Async Page Reader | 📋 Planned |

---

## Part VII — Pages, Records, and Physical Storage

**Purpose**

Study how databases physically organize and store information on persistent media by understanding page architecture, record layouts, slotted pages, physical storage formats, and the engineering decisions behind modern storage engine design.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 136 | Why Databases Use Pages | 📋 Planned |
| Chapter 137 | Pages, Records, and Physical Storage: Engineering Topic 2 | 📋 Planned |
| Chapter 138 | Pages, Records, and Physical Storage: Engineering Topic 3 | 📋 Planned |
| Chapter 139 | Pages, Records, and Physical Storage: Engineering Topic 4 | 📋 Planned |
| Chapter 140 | Pages, Records, and Physical Storage: Engineering Topic 5 | 📋 Planned |
| Chapter 141 | Pages, Records, and Physical Storage: Engineering Topic 6 | 📋 Planned |
| Chapter 142 | Pages, Records, and Physical Storage: Engineering Topic 7 | 📋 Planned |
| Chapter 143 | Pages, Records, and Physical Storage: Engineering Topic 8 | 📋 Planned |
| Chapter 144 | Pages, Records, and Physical Storage: Engineering Topic 9 | 📋 Planned |
| Chapter 145 | Pages, Records, and Physical Storage: Engineering Topic 10 | 📋 Planned |
| Chapter 146 | Pages, Records, and Physical Storage: Engineering Topic 11 | 📋 Planned |
| Chapter 147 | Pages, Records, and Physical Storage: Engineering Topic 12 | 📋 Planned |
| Chapter 148 | Pages, Records, and Physical Storage: Engineering Topic 13 | 📋 Planned |
| Chapter 149 | Pages, Records, and Physical Storage: Engineering Topic 14 | 📋 Planned |
| Chapter 150 | Pages, Records, and Physical Storage: Engineering Topic 15 | 📋 Planned |
| Chapter 151 | Pages, Records, and Physical Storage: Engineering Topic 16 | 📋 Planned |
| Chapter 152 | Pages, Records, and Physical Storage: Engineering Topic 17 | 📋 Planned |
| Chapter 153 | Pages, Records, and Physical Storage: Engineering Topic 18 | 📋 Planned |
| Chapter 154 | Pages, Records, and Physical Storage: Engineering Topic 19 | 📋 Planned |
| Chapter 155 | Pages, Records, and Physical Storage: Engineering Topic 20 | 📋 Planned |
| Chapter 156 | Pages, Records, and Physical Storage: Engineering Topic 21 | 📋 Planned |
| Chapter 157 | Pages, Records, and Physical Storage: Engineering Topic 22 | 📋 Planned |
| Chapter 158 | Pages, Records, and Physical Storage: Engineering Topic 23 | 📋 Planned |
| Chapter 159 | Designing a Database Page Format | 📋 Planned |

---

## Part VIII — File and Table Organization

**Purpose**

Study how database systems organize files, tables, records, and storage layouts on persistent media while understanding the engineering trade-offs behind physical organization, access efficiency, storage utilization, and long-term scalability.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 160 | Database File Organization | 📋 Planned |
| Chapter 161 | File and Table Organization: Engineering Topic 2 | 📋 Planned |
| Chapter 162 | File and Table Organization: Engineering Topic 3 | 📋 Planned |
| Chapter 163 | File and Table Organization: Engineering Topic 4 | 📋 Planned |
| Chapter 164 | File and Table Organization: Engineering Topic 5 | 📋 Planned |
| Chapter 165 | File and Table Organization: Engineering Topic 6 | 📋 Planned |
| Chapter 166 | File and Table Organization: Engineering Topic 7 | 📋 Planned |
| Chapter 167 | File and Table Organization: Engineering Topic 8 | 📋 Planned |
| Chapter 168 | File and Table Organization: Engineering Topic 9 | 📋 Planned |
| Chapter 169 | File and Table Organization: Engineering Topic 10 | 📋 Planned |
| Chapter 170 | File and Table Organization: Engineering Topic 11 | 📋 Planned |
| Chapter 171 | File and Table Organization: Engineering Topic 12 | 📋 Planned |
| Chapter 172 | File and Table Organization: Engineering Topic 13 | 📋 Planned |
| Chapter 173 | File and Table Organization: Engineering Topic 14 | 📋 Planned |
| Chapter 174 | File and Table Organization: Engineering Topic 15 | 📋 Planned |
| Chapter 175 | File and Table Organization: Engineering Topic 16 | 📋 Planned |
| Chapter 176 | File and Table Organization: Engineering Topic 17 | 📋 Planned |
| Chapter 177 | File and Table Organization: Engineering Topic 18 | 📋 Planned |
| Chapter 178 | Choosing a Physical Layout | 📋 Planned |

---

## Part IX — Cloud-Native and Disaggregated Storage Engines

**Purpose**

Study modern cloud-native database storage architectures by understanding storage disaggregation, object storage persistence, remote page access, stateless compute, distributed metadata services, and elastic database infrastructure.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 179 | Why Compute and Storage Disaggregate | 📋 Planned |
| Chapter 180 | Shared Object Storage as Database Persistence | 📋 Planned |
| Chapter 181 | Remote Page and Block Access | 📋 Planned |
| Chapter 182 | Log Is the Database Architectures | 📋 Planned |
| Chapter 183 | Compute Cache Coherence | 📋 Planned |
| Chapter 184 | Stateless Compute Nodes | 📋 Planned |
| Chapter 185 | Elastic Compute Reattachment | 📋 Planned |
| Chapter 186 | Storage-Side Metadata Services | 📋 Planned |
| Chapter 187 | Failure Recovery in Disaggregated Engines | 📋 Planned |
| Chapter 188 | Building a Minimal Disaggregated Storage Prototype | 📋 Planned |

---

## Part X — Buffer Pool Engineering

**Purpose**

Study one of the most critical components of every database management system by understanding buffer pool architecture, page caching strategies, memory management, replacement algorithms, concurrency control, flushing mechanisms, and the engineering principles behind high-performance buffer managers.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 189 | Why Buffer Pools Exist | 📋 Planned |
| Chapter 190 | Buffer Pool Engineering: Engineering Topic 2 | 📋 Planned |
| Chapter 191 | Buffer Pool Engineering: Engineering Topic 3 | 📋 Planned |
| Chapter 192 | Buffer Pool Engineering: Engineering Topic 4 | 📋 Planned |
| Chapter 193 | Buffer Pool Engineering: Engineering Topic 5 | 📋 Planned |
| Chapter 194 | Buffer Pool Engineering: Engineering Topic 6 | 📋 Planned |
| Chapter 195 | Buffer Pool Engineering: Engineering Topic 7 | 📋 Planned |
| Chapter 196 | Buffer Pool Engineering: Engineering Topic 8 | 📋 Planned |
| Chapter 197 | Buffer Pool Engineering: Engineering Topic 9 | 📋 Planned |
| Chapter 198 | Buffer Pool Engineering: Engineering Topic 10 | 📋 Planned |
| Chapter 199 | Buffer Pool Engineering: Engineering Topic 11 | 📋 Planned |
| Chapter 200 | Buffer Pool Engineering: Engineering Topic 12 | 📋 Planned |
| Chapter 201 | Buffer Pool Engineering: Engineering Topic 13 | 📋 Planned |
| Chapter 202 | Buffer Pool Engineering: Engineering Topic 14 | 📋 Planned |
| Chapter 203 | Buffer Pool Engineering: Engineering Topic 15 | 📋 Planned |
| Chapter 204 | Buffer Pool Engineering: Engineering Topic 16 | 📋 Planned |
| Chapter 205 | Buffer Pool Engineering: Engineering Topic 17 | 📋 Planned |
| Chapter 206 | Buffer Pool Engineering: Engineering Topic 18 | 📋 Planned |
| Chapter 207 | Buffer Pool Engineering: Engineering Topic 19 | 📋 Planned |
| Chapter 208 | Buffer Pool Engineering: Engineering Topic 20 | 📋 Planned |
| Chapter 209 | Buffer Pool Engineering: Engineering Topic 21 | 📋 Planned |
| Chapter 210 | Buffer Pool Engineering: Engineering Topic 22 | 📋 Planned |
| Chapter 211 | Buffer Pool Engineering: Engineering Topic 23 | 📋 Planned |
| Chapter 212 | Buffer Pool Engineering: Engineering Topic 24 | 📋 Planned |
| Chapter 213 | Building a Buffer Pool | 📋 Planned |

---

## Volume II Glossary

| Topic | Status |
|--------|--------|
| Chapter 214 — Volume II Glossary | 📋 Planned |

---

## Volume II Summary

The second volume builds the storage foundation of modern database systems by exploring asynchronous I/O, Linux io_uring, direct storage access, physical page organization, record layouts, file and table organization, cloud-native and disaggregated storage architectures, and buffer pool engineering. By understanding how databases efficiently move, organize, cache, and manage data between persistent storage and memory, readers develop the systems-level knowledge required to understand storage engines, indexing structures, transaction processing, recovery mechanisms, and the internal architecture of high-performance database management systems.

---

## Volume III — Foundation: Indexing Foundations to Concurrent and Advanced Tree Indexes

**Learning Level:** Foundation

**Theme**

Study the internal architecture of database indexing systems by understanding why indexes exist, how B-Trees and B+Trees work, and how modern database engines implement scalable concurrent tree indexes.

**Objective**

Build a solid foundation in database indexing by learning index design principles, search tree architectures, production B+Tree engineering, and concurrent indexing techniques that enable fast, scalable, and reliable data retrieval in modern database systems.

---

## Part XI — Indexing Foundations

**Purpose**

Study the fundamental principles of database indexing by understanding why indexes exist, how they improve query performance, the trade-offs involved in index design, and the situations where indexes can either accelerate or degrade database performance.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 215 | Why Indexes Exist | 📋 Planned |
| Chapter 216 | Indexing Foundations: Engineering Topic 2 | 📋 Planned |
| Chapter 217 | Indexing Foundations: Engineering Topic 3 | 📋 Planned |
| Chapter 218 | Indexing Foundations: Engineering Topic 4 | 📋 Planned |
| Chapter 219 | Indexing Foundations: Engineering Topic 5 | 📋 Planned |
| Chapter 220 | Indexing Foundations: Engineering Topic 6 | 📋 Planned |
| Chapter 221 | Indexing Foundations: Engineering Topic 7 | 📋 Planned |
| Chapter 222 | Indexing Foundations: Engineering Topic 8 | 📋 Planned |
| Chapter 223 | Indexing Foundations: Engineering Topic 9 | 📋 Planned |
| Chapter 224 | Indexing Foundations: Engineering Topic 10 | 📋 Planned |
| Chapter 225 | Indexing Foundations: Engineering Topic 11 | 📋 Planned |
| Chapter 226 | Indexing Foundations: Engineering Topic 12 | 📋 Planned |
| Chapter 227 | Indexing Foundations: Engineering Topic 13 | 📋 Planned |
| Chapter 228 | Indexing Foundations: Engineering Topic 14 | 📋 Planned |
| Chapter 229 | Indexing Foundations: Engineering Topic 15 | 📋 Planned |
| Chapter 230 | Indexing Foundations: Engineering Topic 16 | 📋 Planned |
| Chapter 231 | Indexing Foundations: Engineering Topic 17 | 📋 Planned |
| Chapter 232 | Indexing Foundations: Engineering Topic 18 | 📋 Planned |
| Chapter 233 | Indexing Foundations: Engineering Topic 19 | 📋 Planned |
| Chapter 234 | Indexing Foundations: Engineering Topic 20 | 📋 Planned |
| Chapter 235 | Indexing Foundations: Engineering Topic 21 | 📋 Planned |
| Chapter 236 | Indexing Foundations: Engineering Topic 22 | 📋 Planned |
| Chapter 237 | When an Index Makes Performance Worse | 📋 Planned |

---

## Part XII — B-Trees and B+Trees

**Purpose**

Study the world's most important database indexing structures by understanding binary search trees, B-Trees, B+Trees, node organization, balancing algorithms, page layouts, and the engineering techniques behind production-grade tree indexes.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 238 | Binary Search Trees | 📋 Planned |
| Chapter 239 | B-Trees and B+Trees: Engineering Topic 2 | 📋 Planned |
| Chapter 240 | B-Trees and B+Trees: Engineering Topic 3 | 📋 Planned |
| Chapter 241 | B-Trees and B+Trees: Engineering Topic 4 | 📋 Planned |
| Chapter 242 | B-Trees and B+Trees: Engineering Topic 5 | 📋 Planned |
| Chapter 243 | B-Trees and B+Trees: Engineering Topic 6 | 📋 Planned |
| Chapter 244 | B-Trees and B+Trees: Engineering Topic 7 | 📋 Planned |
| Chapter 245 | B-Trees and B+Trees: Engineering Topic 8 | 📋 Planned |
| Chapter 246 | B-Trees and B+Trees: Engineering Topic 9 | 📋 Planned |
| Chapter 247 | B-Trees and B+Trees: Engineering Topic 10 | 📋 Planned |
| Chapter 248 | B-Trees and B+Trees: Engineering Topic 11 | 📋 Planned |
| Chapter 249 | B-Trees and B+Trees: Engineering Topic 12 | 📋 Planned |
| Chapter 250 | B-Trees and B+Trees: Engineering Topic 13 | 📋 Planned |
| Chapter 251 | B-Trees and B+Trees: Engineering Topic 14 | 📋 Planned |
| Chapter 252 | B-Trees and B+Trees: Engineering Topic 15 | 📋 Planned |
| Chapter 253 | B-Trees and B+Trees: Engineering Topic 16 | 📋 Planned |
| Chapter 254 | B-Trees and B+Trees: Engineering Topic 17 | 📋 Planned |
| Chapter 255 | B-Trees and B+Trees: Engineering Topic 18 | 📋 Planned |
| Chapter 256 | B-Trees and B+Trees: Engineering Topic 19 | 📋 Planned |
| Chapter 257 | B-Trees and B+Trees: Engineering Topic 20 | 📋 Planned |
| Chapter 258 | B-Trees and B+Trees: Engineering Topic 21 | 📋 Planned |
| Chapter 259 | B-Trees and B+Trees: Engineering Topic 22 | 📋 Planned |
| Chapter 260 | B-Trees and B+Trees: Engineering Topic 23 | 📋 Planned |
| Chapter 261 | B-Trees and B+Trees: Engineering Topic 24 | 📋 Planned |
| Chapter 262 | B-Trees and B+Trees: Engineering Topic 25 | 📋 Planned |
| Chapter 263 | B-Trees and B+Trees: Engineering Topic 26 | 📋 Planned |
| Chapter 264 | B-Trees and B+Trees: Engineering Topic 27 | 📋 Planned |
| Chapter 265 | B-Trees and B+Trees: Engineering Topic 28 | 📋 Planned |
| Chapter 266 | B-Trees and B+Trees: Engineering Topic 29 | 📋 Planned |
| Chapter 267 | Production B+Tree Engineering | 📋 Planned |

---

## Part XIII — Concurrent and Advanced Tree Indexes

**Purpose**

Study how modern database systems implement highly concurrent and scalable tree indexes by understanding locking and latching mechanisms, concurrent tree operations, synchronization strategies, structural modifications, and advanced index architectures used in production database engines.

| Chapter | Purpose | Status |
|---------|---------|--------|
| Chapter 268 | Locks vs Latches | 📋 Planned |
| Chapter 269 | Concurrent and Advanced Tree Indexes: Engineering Topic 2 | 📋 Planned |
| Chapter 270 | Concurrent and Advanced Tree Indexes: Engineering Topic 3 | 📋 Planned |
| Chapter 271 | Concurrent and Advanced Tree Indexes: Engineering Topic 4 | 📋 Planned |
| Chapter 272 | Concurrent and Advanced Tree Indexes: Engineering Topic 5 | 📋 Planned |
| Chapter 273 | Concurrent and Advanced Tree Indexes: Engineering Topic 6 | 📋 Planned |
| Chapter 274 | Concurrent and Advanced Tree Indexes: Engineering Topic 7 | 📋 Planned |
| Chapter 275 | Concurrent and Advanced Tree Indexes: Engineering Topic 8 | 📋 Planned |
| Chapter 276 | Concurrent and Advanced Tree Indexes: Engineering Topic 9 | 📋 Planned |
| Chapter 277 | Concurrent and Advanced Tree Indexes: Engineering Topic 10 | 📋 Planned |
| Chapter 278 | Concurrent and Advanced Tree Indexes: Engineering Topic 11 | 📋 Planned |
| Chapter 279 | Concurrent and Advanced Tree Indexes: Engineering Topic 12 | 📋 Planned |
| Chapter 280 | Concurrent and Advanced Tree Indexes: Engineering Topic 13 | 📋 Planned |
| Chapter 281 | Concurrent and Advanced Tree Indexes: Engineering Topic 14 | 📋 Planned |
| Chapter 282 | Concurrent and Advanced Tree Indexes: Engineering Topic 15 | 📋 Planned |
| Chapter 283 | Concurrent and Advanced Tree Indexes: Engineering Topic 16 | 📋 Planned |
| Chapter 284 | Concurrent and Advanced Tree Indexes: Engineering Topic 17 | 📋 Planned |
| Chapter 285 | Concurrent and Advanced Tree Indexes: Engineering Topic 18 | 📋 Planned |
| Chapter 286 | Concurrent and Advanced Tree Indexes: Engineering Topic 19 | 📋 Planned |
| Chapter 287 | Concurrent and Advanced Tree Indexes: Engineering Topic 20 | 📋 Planned |
| Chapter 288 | Concurrent and Advanced Tree Indexes: Engineering Topic 21 | 📋 Planned |
| Chapter 289 | Choosing a Tree Index Architecture | 📋 Planned |

---

## Volume III Glossary

| Topic | Status |
|--------|--------|
| Chapter 290 — Volume III Glossary | 📋 Planned |

---

## Volume III Summary

Volume III establishes the complete foundation of database indexing by exploring why indexes exist, how they accelerate data retrieval, the architecture and implementation of B-Trees and B+Trees, and the concurrency techniques required to build scalable production-grade tree indexes. Readers gain a deep understanding of index design principles, tree balancing, storage organization, synchronization mechanisms, and advanced indexing strategies that prepare them for modern write-optimized storage engines, specialized indexing structures, and high-performance query execution in later volumes.

---

## Continue Reading

You have completed **Part 1** of the **Database Engineering Handbook Remastered Master Curriculum**, covering the complete **Foundation** curriculum from **Volume I** through **Volume III**.

Continue your learning journey with **Part 2**, which begins with:

- **Volume IV — Intermediate: LSM Trees, Log-Structured Storage, and Modern Write-Optimized Engines**

See **`part-2.md`** to continue the curriculum.
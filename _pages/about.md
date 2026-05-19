---
permalink: /
title: "Elixir Security and Concurrency Summer School"
excerpt: "Inaugural Intensive Course on Resilient & Distributed Systems Design"
author_profile: false # Set to true if you want to use the left sidebar from _config.yml
---

## Elixir Security and Concurrency Summer School

Join us for the inaugural Elixir Security and Concurrency Summer School. Concurrent and distributed runtime architectures impact everyone's live-production systems, whether they are aware of it or not. This intensive program aims to introduce students to the paradigms of developing novel backend architectures focused solely on horizontal scaling and fault tolerance, regardless of the potential edge cases. Participants will enhance their knowledge of actor-model systems, the runtime threats or race conditions they face, and the protective, robust engineering measures that can be employed to counteract these system failures.

---

## Course Overview
The Elixir Security and Concurrency Summer School will educate students on the engineering principles of the BEAM virtual machine, including process registration bottlenecks, dynamic supervisor manipulation, clustered sabotage networks, and state resilience. The course will also cover practical defense mechanisms to safeguard the data consistency and high availability of these architectures. Participants will engage in hands-on labs, interactive network clusters, and practical testing suites.

---

## Technical Syllabus

### DAY 1: Functional Foundations & Stateful Actors
* **Elixir Basics:** Deep dive into modules, functions, pattern matching, guards, the pipe operator, structs, and tagged tuples.
* **Structs & Validation Rules:** Constructing domain models with explicit validation schemas using functional pipelines.
* **Card Generation Subsystem:** Designing a core module that handles the algorithmic, random generation of card datasets.
* **Validation Engine:** Leveraging pattern matching configurations to enforce system invariances off-loaded from traditional conditional logic.
* **The Player GenServer:** State management architecture holding atomic game metrics (scores, current card states, and cards processed counters).

### DAY 2: Resilient Clusters & Reactive Flow
* **Supervisors & Process Registration:** Implementing custom supervision trees, understanding global/local registries, and exploring why the "let it crash" philosophy matters under stress.
* **PubSub & Live Leaderboards:** Architecting real-time state broadcasts tracking player scores across decoupled system boundaries.
* **The Sabotage Mechanic:** Simulating cluster attacks by routing targeted signals directly to explicit Player Process Identifiers (PIDs) across distributed nodes.
* **Game Cycle & Match Flow:** Designing a timed execution loop for game rounds, implementing synchronization barriers to delay runtime state initialization until all nodes signal readiness.

### DAY 3: Background Pipelines & Verification
* **Oban Background Jobs:** Exploring transactional job processing, analyzing how queue-backed systems differ from bare asynchronous processes, job scheduling strategies, and exponential backoff retry configurations.
* **Testing Concurrent Systems:** Asserting properties on asynchronous workflows, mailbox behaviors, and isolation boundaries inside the test suite.

---

## Administrative Details

* **Timeline:** This summer school takes place July 28–30, 2026.
* **Instructors:** Andrei Ouatu, Andrei Dugăeșescu, Alex Deonise, Răzvan Rughiniș.
* **Enrollment:** You need to enroll to participate. Space is limited due to node cluster sandbox infrastructure.

### Resources & Links
* **Repository Hub:** You can find the courses and technical lab demos here: [Elixir Security and Concurrency Summer School Courses](https://github.com/yourusername/your-repo-name)
* **Application Portal:** Register now for the summer school session: [Register for Elixir Summer School](https://forms.example.org)

---

## Organizational Partners
The Elixir Security and Concurrency Summer School is organized by the privacy and systems community at the **Faculty of Automatic Control and Computers, University POLITEHNICA of Bucharest**, supported by our industry partners: **Keysight Technologies Romania** (our main industry partner).
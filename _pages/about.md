---
permalink: /
title: "Elixir Summer School 2026"
excerpt: "Inaugural Intensive Course on Resilient & Distributed Systems Design"
author_profile: true # Set to true if you want to use the left sidebar from _config.yml
---

## Elixir Summer School

Join us for the first edition of Elixir Summer School! This summer we will be introducing students to a functional programming language designed for handling millions of processes at once. From core functional foundations to complex distributed state management, the lessons are structured to teach the essentials of Elixir programming. Participants will build a complete, fault-tolerant game engine, mastering GenServers for state management, supervision trees for crash recovery, PubSub for including in your registration form down below to increase the chances of getting accepted, and Oban for background job processing. By the end, attendees will possess the practical engineering skills needed to test concurrent workflows and construct robust, highly scalable backend architectures.

---

## Administrative Details

* **Timeline:** This summer school takes place June 25–28, 2026.
* **Instructors:** Dragoș Dumitru.
* **Enrollment:** You need to enroll to participate.

### Registration
* **Repository Hub:** You can find the courses and technical lab demos here: [COMING SOON](https://github.com/yourusername/your-repo-name)
* **Application Portal:** Register now for the summer school session: [Google Forms](https://docs.google.com/forms/d/e/1FAIpQLScAj9sUBs-hb0u9gQuDNitn9t9Gm1IKvuzWsQmoD7GpyB4hCg/viewform?usp=dialog)

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

### DAY 4: Rubber meets the road
* **Elixir Hackathon:** At the end of our training we will hold a hackathon based on which our partners at PDQ will offer 5 summer internships for july, august, september and prizes for the best projects

---

## Organizational Partners
The Elixir Security and Concurrency Summer School is organized by the **Faculty of Automatic Control and Computers, University POLITEHNICA of Bucharest**, supported by our industry partners: **PDQ**.
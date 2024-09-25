---
title: "Schedule"
layout: splash
---

<style type="text/css">
span.discussion { color: #dc267f; font-weight: bold }
span.lecture { color: #fe6100; font-weight: bold }
</style>

## Schedule of topics and readings

This schedule is tentative, and it is neither [_sound_](https://en.wikipedia.org/wiki/Soundness) (that is, if a particular reading or topic is listed here, that doesn't mean we'll cover it!) nor [_complete_](https://en.wikipedia.org/wiki/Completeness_(logic)) (that is, if a particular reading or topic is *not* listed here, that doesn't mean we *won't* cover it!).

The course will alternate between <span class="discussion">Discussion</span> and <span class="lecture">Lecture</span> days.  For days marked <span class="discussion">Discussion</span>, you must turn in your [reading response](course-overview.html#what-to-include-in-your-reading-response) for that day's reading assignment on Canvas **by noon Pacific time on the day of class**.

| Date             | Topic                                          | Notes
|------------------|------------------------------------------------|------------------------------------------------------------------------------------------------------------
| Friday, 9/27     | [Course overview](course-overview.html)        | 
| Monday, 9/30     | <span class="lecture">Lecture</span>: distributed systems: what and why?; time and clocks; Lamport diagrams | Start-of-course survey due by start of class today
| Wednesday, 10/2  | <span class="discussion">Discussion</span>: Jim Waldo et al., ["A Note on Distributed Computing" (1994)](readings/note-distributed-computing.pdf) | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 10/9
| Friday, 10/4     | <span class="lecture">Lecture</span>: causality and happens-before; network models; partial orders; total orders; Lamport clocks
| Monday, 10/7     | <span class="discussion">Discussion</span>: Leslie Lamport, ["Time, Clocks, and the Ordering of Events in a Distributed System" (CACM 1978)](readings/time-clocks.pdf) **(skip the section "Physical Clocks")**  | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 10/14
| Wednesday, 10/9  | <span class="lecture">Lecture</span>: vector clocks; properties of executions; delivery vs. receiving; FIFO delivery; causal delivery
| Friday, 10/11    | <span class="discussion">Discussion</span>: Reinhard Schwarz and Friedemann Mattern, ["Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail" (_Distributed Computing_, 1994)](readings/holy-grail.pdf) **(sections 1-3 and 6 only)**  | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 10/18
| Monday, 10/14    | <span class="lecture">Lecture</span>: totally-ordered delivery; implementing FIFO delivery; implementing causal broadcast
| Wednesday, 10/16 | <span class="discussion">Discussion</span>: Kenneth Birman, André Schiper, and Pat Stephenson, ["Lightweight Causal and Atomic Group Multicast" (TOCS, 1991)](readings/cbcast.pdf) **(sections 1-5 only)** | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 10/23
| Friday, 10/18    | <span class="lecture">Lecture</span>: uses of causality in distributed systems; consistent snapshots; Chandy-Lamport snapshot algorithm
| Monday, 10/21    | <span class="discussion">Discussion</span>: K. Mani Chandy and Leslie Lamport, ["Distributed Snapshots: Determining Global States of Distributed Systems" (TOCS, 1985)](readings/chandy.pdf) | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 10/28
| Wednesday, 10/23 | No class (Lindsey at OOPSLA) | If you want to, check out the [paper we're presenting at OOPSLA](https://2024.splashcon.org/details/splash-2024-oopsla/20/Inductive-diagrams-for-causal-reasoning) -- it's related to this class!
| Friday, 10/25    | <span class="lecture">Lecture (on Zoom)</span>: Chandy-Lamport wrap-up; centralized vs. decentralized algorithms; recap of delivery guarantees and protocols; reliable delivery; safety and liveness; the CAP trade-off
| Monday, 10/28    | <span class="discussion">Discussion</span>: Seth Gilbert and Nancy A. Lynch, ["Perspectives on the CAP Theorem" (IEEE Computer, 2012)](readings/cap-perspectives.pdf) | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 11/4
| Wednesday, 10/30 | <span class="lecture">Lecture</span>: fault classification and fault models; two generals problem
| Friday, 11/1     | <span class="discussion">Discussion</span>: Joseph Y. Halpern and Yoram Moses, ["Knowledge and Common Knowledge in a Distributed Environment" (JACM, 1990)](readings/common-knowledge.pdf) **(sections 1-4 only)** | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 11/8
| Monday, 11/4     | <span class="lecture">Lecture</span>: implementing reliable delivery; idempotence; at-least-once/at-most-once/exactly-once delivery; replication; total order vs. determinism; primary-backup replication; chain replication; latency and throughput
| Wednesday, 11/6  | <span class="discussion">Discussion</span>: Robbert van Renesse and Fred B. Schneider, ["Chain Replication for Supporting High Throughput and Availability" (OSDI 2004)](readings/chain-replication.pdf) | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 11/13
| Friday, 11/8     | **Guest lecture: [Srinivasan (Sesh) Seshadri](https://www.linkedin.com/in/srinivasanseshadri/)**
| Monday, 11/11    | No class (Veterans Day)
| Wednesday, 11/13 | <span class="lecture">Lecture</span>: handling node failure in replication protocols; introduction to consensus; problems equivalent to consensus; the FLP result; introduction to Paxos
| Friday, 11/15    | <span class="discussion">Discussion</span>: Leslie Lamport, ["Paxos Made Simple" (2001)](readings/paxos-simple.pdf) | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 11/22
| Monday, 11/18    | <span class="lecture">Lecture</span>: Paxos: the interesting parts; Multi-Paxos; fault tolerance of Paxos; brief mention of other consensus protocols: Viewstamped Replication, Zab, Raft; passive vs. active (state machine) replication
| Wednesday, 11/20 | <span class="discussion">Discussion</span>: Tushar Chandra, Robert Griesemer, and Joshua Redstone, ["Paxos Made Live: An Engineering Perspective" (invited talk, PODC 2007)](readings/paxos-made-live.pdf) | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 11/27
| Friday, 11/22    | <span class="lecture">Lecture</span>: MapReduce
| Monday, 11/25    | <span class="discussion">Discussion</span>: Jeffrey Dean and Sanjay Ghemawat, ["MapReduce: Simplified Data Processing on Large Clusters" (OSDI 2004)](readings/mapreduce.pdf)  | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on Friday, 12/2
| Wednesday, 11/27 | TBD
| Friday, 11/29    | No class (Thanksgiving break)
| Monday, 12/2     | <span class="lecture">Lecture (on Zoom)</span>: eventual consistency; strong convergence and strong eventual consistency; intro to application-specific conflict resolution; network partitions; availability; the consistency/availability trade-off; anti-entropy with Merkle trees; gossip; quorum consistency
| Wednesday, 12/4  | <span class="discussion">Discussion (on Zoom)</span>: Giuseppe DeCandia et al., ["Dynamo: Amazon’s Highly Available Key-value Store" (SOSP 2007)](readings/amazon-dynamo.pdf)  | Reading response due at noon; scribes' wiki write-up due 11:59:59pm PT on 12/11
| Friday, 12/6     | <span class="lecture">Lecture (on Zoom): </span> Wrap-up and exam review
| Tuesday, 12/10   | **Final exam**, 4–7pm




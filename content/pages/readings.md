---
content_type: page
description: This section provides information on the course texts, the schedule of
  readings by lecture topic, and a list of supplementary readings.
draft: false
learning_resource_types:
- Readings
ocw_type: CourseSection
title: Readings
uid: 9419cc1a-8cb6-0caa-1994-57fe90cae803
---
## Texts

### Required

The primary source will be the book *Distributed Algorithms* by Prof. Nancy Lynch.

\[Lynch\] = Lynch, Nancy. *Distributed Algorithms*. Burlington, MA: Morgan Kaufmann, 1996. ISBN: 9781558603486.

Errata ({{% resource_link f6ec6a72-ce07-2257-3b3c-d087cfbecafb "PDF" %}})

This book has gone through many printings, but we have made no changes since the fourth printing, so fourth printings or later are just fine. Known errata for early printings are collected in errata lists. The book refers to many papers from the research literature on distributed algorithms; you might want to track down and read some of these.

### Recommended

Other books that you will find useful are:

\[Attiya and Welch\] = Attiya, Hagit, and Jennifer Welch. *Distributed Computing: Fundamentals, Simulations, and Advanced Topics*. 2nd ed. New York, NY: Wiley-Interscience, 2004. ISBN:9780471453246.

This is another textbook on distributed algorithms, initially published a little after the Lynch book. It now has a second edition. The material covered overlaps quite a lot with the Lynch book, though Attiya and Welch do cover some topics, like clock synchronization, that Lynch does not cover. The style is a little less formal.

\[Herlihy and Shavit\] = Herlihy, Maurice, and Nir Shavit. *The Art of Multiprocessor Programming*. Burlington, MA: Morgan Kaufmann, 2008. ISBN: 9780123705914.

This undergraduate textbook covers basic algorithms and techniques for multiprocessor programming.

\[Guerraoui and Kapalka\] = Guerraoui, Rachid, and Michal Kapalka. *Transactional Memory: The Theory*. San Rafael, CA: Morgan and Claypool, 2010. ISBN: 9781608450114.

This monograph presents basic theoretical results about the possibility and costs of implementing transactional memory for shared-memory multiprocessors.

\[Dolev\] = ![Buy at MIT Press](/images/mp_logo.gif) Dolev, Shlomi. *Self-Stabilization*. Cambridge, MA: MIT Press, 2000. ISBN: 9780262041782.

This book gives a good description of self-stabilizing distributed algorithms. Self-stabilization is a strong kind of fault-tolerance, which we will study near the end of the course.

Kaynar, Disun, Nancy Lynch, Roberto Segala, and Frits Vaandrager. *The Theory of Timed I/O Automata*. 2nd ed. San Rafael, CA: Morgan and Claypool, 2010. ISBN: 9781608450022.

This monograph presents a basic modeling framework, Timed I/O Automata (TIOA), for describing and analyzing distributed algorithms.

In addition, some research papers that are not covered in the textbook will be covered in class and on problem sets. These papers are listed in the [supplementary readings](#Supplementary_Readings).

## Reading by Session

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
SES #
{{< thclose >}}{{< thopen >}}
TOPICS
{{< thclose >}}{{< thopen >}}
READINGS
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
1
{{< tdclose >}}{{< tdopen >}}
Course overview. Synchronous networks. Leader election in synchronous ring networks.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapters 1 and 2, sections 3.1 to 3.5.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
2
{{< tdclose >}}{{< tdopen >}}
Leader election in rings. Basic computational tasks in general synchronous networks: leader election. Breadth-first search. Broadcast and convergecast. Shortest paths.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Section 3.6, and sections 4.1 to 4.3.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
3
{{< tdclose >}}{{< tdopen >}}
Spanning trees. Shortest paths (Bellman-Ford). Minimum spanning trees. Maximal independent sets (summary).
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Sections 4.3 to 4.5 (skip 4.5.3).
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
4
{{< tdclose >}}{{< tdopen >}}
Fault-tolerant consensus. Link failures: the two generals problem. Process failures (stopping, Byzantine). Algorithms for agreement with stopping and Byzantine failures. Exponential information gathering.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Sections 5.1 and 6.1 to 6.3.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
5
{{< tdclose >}}{{< tdopen >}}
Number-of-processor bounds for Byzantine agreement. Weak Byzantine agreement. Time bounds for consensus problems.
{{< tdclose >}}{{< tdopen >}}

\[Lynch\] Sections 6.4 to 6.7.

Aguilera, Marcos Kawazoe, and Sam Toueg. "A Simple Bivalency Proof that *t*\-Resilient Consensus Requires *t*+1 Rounds." *Information Processing Letters* 71, nos. 3-4 (August 1999): 155-158.

### Optional

Keidar, Idit, and Sergio Rajsbaum. "{{% resource_link "fd77e5b6-6a4a-47ce-b7b2-bfce8b40290c" "A Simple Proof of the Uniform Consensus Synchronous Lower Bound" %}}." *Information Processing Letters* 85, no. 1 (January 2003): 47-52.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
6
{{< tdclose >}}{{< tdopen >}}
*k*\-set-agreement. Approximate agreement. Distributed commit.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapter 7.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
7
{{< tdclose >}}{{< tdopen >}}
Asynchronous distributed computing. Formal modeling of asynchronous systems using interacting state machines (I/O automata). Proving correctness of distributed algorithms.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapter 8.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
8
{{< tdclose >}}{{< tdopen >}}
Non-fault-tolerant algorithms for asynchronous networks. Leader election, breadth-first search, shortest paths, broadcast and convergecast.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapters 14 and 15.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
9
{{< tdclose >}}{{< tdopen >}}
Spanning trees. Gallager *et al*. minimum spanning trees.
{{< tdclose >}}{{< tdopen >}}

\[Lynch\] Sections 15.3 to 15.5.

Gallager, R. G., P. A. Humblet, and P. M. Spira. "A Distributed Algorithm for Minimum-Weight Spanning Trees." *ACM Transactions on Programming Languages and Systems* 5, no. 1 (January 1983): 66-77.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
10
{{< tdclose >}}{{< tdopen >}}
Synchronizers. Synchronizer applications. Synchronous *vs*. asynchronous distributed systems.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapter 16.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
11
{{< tdclose >}}{{< tdopen >}}
Time, clocks, and the ordering of events. State-machine simulation. Vector timestamps.
{{< tdclose >}}{{< tdopen >}}

\[Lynch\] Chapter 18.

Lamport, Leslie. "Time, Clocks, and the Ordering of Events in a Distributed System." *Communications of the Association for Computing Machinery* 21, no. 7 (July 1978): 558-565. ({{% resource_link "4df25ac7-1c72-4c4a-814f-296fa103438f" "PDF" %}})

Mattern, Friedemann. "Virtual Time and Global States of Distributed Systems." In *Parallel and Distributed Algorithms: Proceedings of the International Workshop on Parallel and Distributed Algorithms (Chateau de Bonas, Gers, France, October, 1988)*. Edited by Michel Cosnard, et al. Amsterdam, The Netherlands: North Holland, 1989, 215-226. ISBN: 9780444873675. Reprint, Yang, Zhonghua, and T. Anthony Marsland, eds. "Virtual Time and Global States of Distributed Systems." *In Global States and Time in Distributed Systems*. Los Alamitos, CA: IEEE Computer Society Press, 1994, pp. 123-133. ISBN: 9780818653001.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
12
{{< tdclose >}}{{< tdopen >}}
Stable property detection. Distributed termination. Global snapshots. Deadlock detection.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapter 19.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
13
{{< tdclose >}}{{< tdopen >}}
Asynchronous shared-memory systems. The mutual exclusion problem. Mutual exclusion algorithms: Dijkstra’s algorithm, Peterson’s algorithm, and Lamport’s Bakery algorithm.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapter 9 and sections 10.1 to 10.7.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
14
{{< tdclose >}}{{< tdopen >}}
More mutual exclusion algorithms. Bounds on shared memory for mutual exclusion. Resource allocation. The Dining Philosophers problem.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Sections 10.6 to 10.8, and 10.9.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
15
{{< tdclose >}}{{< tdopen >}}
Shared-memory multiprocessors. Contention, caching, locality. Practical mutual exclusion algorithms. Reading/writing locks.
{{< tdclose >}}{{< tdopen >}}

\[Herlihy and Shavit\] Chapter 7.

\[Lynch\] Chapter 11.

Mellor-Crummey, John M., and Michael L. Scott. "Algorithms for Scalable Synchronization on Shared-Memory Multiprocessors." *ACM Transactions on Computer Systems* 9, no. 1 (February 1991): 21-65.

### Optional

Magnussen, Peter, Anders Landin, and Erik Hagersten. "Queue Locks on Cache Coherent Multiprocessors." *Proceedings of the 8th International Symposium on Parallel Processing*, 1994, pp. 165-171.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
16
{{< tdclose >}}{{< tdopen >}}
Impossibility of consensus in asynchronous, fault-prone, shared-memory systems.
{{< tdclose >}}{{< tdopen >}}

\[Lynch\] Chapters 11 and 12.

Fischer, Michael J., Nancy A. Lynch, and Michael S. Paterson. "Impossibility of Distributed Consensus with One Faulty Process." *Journal of the Association for Computing Machinery* 32, no. 2 (April 1985): 374-382.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
17
{{< tdclose >}}{{< tdopen >}}
Atomic objects
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapter 13 (sections 13.1 and 13.2).
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
18
{{< tdclose >}}{{< tdopen >}}
Atomic snapshot algorithms. Atomic read/write register algorithms.
{{< tdclose >}}{{< tdopen >}}
\[Lynch\] Chapter 13 (sections 13.3 and 13.4).
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
19
{{< tdclose >}}{{< tdopen >}}
List algorithms: locking algorithms, optimistic algorithms, lock-free algorithms, lazy algorithms.
{{< tdclose >}}{{< tdopen >}}
\[Herlihy and Shavit\] Chapter 9.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
20
{{< tdclose >}}{{< tdopen >}}
Transactional memory: obstruction-free and lock-based implementations.
{{< tdclose >}}{{< tdopen >}}

\[Herlihy and Shavit\] Chapter 18.

\[Guerraoui and Kapalka\] Chapters 1 to 4.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
21
{{< tdclose >}}{{< tdopen >}}
Wait-free computability. The wait-free consensus hierarchy.
{{< tdclose >}}{{< tdopen >}}

Herlihy, Maurice. "Wait-Free Synchronization." *ACM Transactions on Programming Languages and Systems* 13, no. 1 (January 1991): 124-149.

\[Attiya and Welch\] Chapter 15.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
22
{{< tdclose >}}{{< tdopen >}}
Wait-free vs. *f*\-fault-tolerant atomic objects. Boosting fault-tolerance.
{{< tdclose >}}{{< tdopen >}}

Borowsky, Elizabeth, Eli Gafni, Nancy Lynch, and Sergio Rajsbaum. "The BG Distributed Simulation Algorithm." *Distributed Computing* 14 (2001): 127-146.

Attie, Paul, Rachid Guerraoui, Petr Kouznetsov, Nancy Lynch, and Sergio Rajsbaum. "The Impossibility of Boosting Distributed Service Resilience." Submitted for journal publication, September 2009.

Chandra, Tushar D., Vassos Hadzilacos, Prasad Jayanti, and Sam Toueg. "Generalized Irreducibility of Consensus and the Equivalence of *t*\-Resilient and Wait-Free Implementations of Consensus." *SIAM Journal on Computing* 34, no. 2 (2004): 333-357.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
23
{{< tdclose >}}{{< tdopen >}}
Asynchronous network model vs. asynchronous shared-memory model. Impossibility of consensus in asynchronous networks. Failure detectors and consensus. Paxos consensus algorithm.
{{< tdclose >}}{{< tdopen >}}

\[Lynch\] Chapter 17.

Lamport, Leslie. "The Part-Time Parliament." *ACM Transactions on Computer Systems* 16, no. 2 (May 1998): 133-169. Also available as Research Report 49, Digital Equipment Corporation Systems Research Center, Palo Alto, CA, September 1989.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
24
{{< tdclose >}}{{< tdopen >}}
Self-stabilizing algorithms
{{< tdclose >}}{{< tdopen >}}
\[Dolev\] Chapter 2.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
25
{{< tdclose >}}{{< tdopen >}}
Timing-based systems. Modeling and verification. Timing-based algorithms for mutual exclusion and consensus. Clock synchronization.
{{< tdclose >}}{{< tdopen >}}

\[Lynch\] Chapters 23 to 25.

\[Attiya and Welch\] Section 6.3 and chapter 13.

{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

## {{< anchor "Supplementary_Readings" >}}Supplementary Readings{{< /anchor >}}

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
TOPICS
{{< thclose >}}{{< thopen >}}
READINGS
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
Dijkstra Prize papers
{{< tdclose >}}{{< tdopen >}}

In each of the years 2000-2009, a prize has been awarded to a research paper that has had a strong impact on research in the area of distributed algorithms. The prize was originally called the "PODC Influential Paper Award." After the death of Edsger Dijkstra, one of the pioneers of the field, in August 2002, the prize was renamed the "Dijkstra Prize."

We will study the key contributions of most of these papers during this semester. In case you want to read the original papers for yourselves, here is a list:

Lamport, Leslie. "Time, Clocks, and the Ordering of Events in a Distributed System." *Communications of the Association for Computing Machinery* 21, no. 7 (July 1978): 558-565. ({{% resource_link "4df25ac7-1c72-4c4a-814f-296fa103438f" "PDF" %}})

Fischer, Michael J., Nancy A. Lynch, and Michael S. Paterson. "Impossibility of Distributed Consensus with One Faulty Process." *Journal of the Association for Computing Machinery* 32, no. 2 (April 1985): 374-382.

Dijkstra, Edsger W. "Self-Stabilizing Systems in Spite of Distributed Control." *Communications of the Association for Computing Machinery* 17, no. 11 (November 1974): 643-644.

Herlihy, Maurice. "Wait-Free Synchronization." *ACM Transactions on Programming Languages and Systems* 13, no. 1 (January 1991): 124-149.

Gallager, R. G., P. A. Humblet, and P. M. Spira. "A Distributed Algorithm for Minimum-Weight Spanning Trees." *ACM Transactions on Programming Languages and Systems* 5, no. 1 (January 1983): 66-77.

Pease, M., R. Shostak, and L. Lamport. "Reaching Agreement in the Presence of Faults." *Journal of the Association for Computing Machinery* 27, no. 2 (April 1980): 228-234. ({{% resource_link "1468be91-5a52-435d-a860-76ffe914bc60" "PDF" %}})

Mellor-Crummey, John M., and Michael L. Scott. "Algorithms for Scalable Synchronization on Shared-Memory Multiprocessors." *ACM Transactions on Computer Systems* 9, no. 1 (February 1991): 21-65.

Dwork, Cynthia, Nancy Lynch, and Larry Stockmeyer. "Consensus in the Presence of Partial Synchrony." *Journal of the Association for Computing Machinery* 35, no. 2 (April 1988): 288-323.

Awerbuch, Baruch, and David Peleg. "Sparse Partitions." Proceedings of the 31st Annual IEEE Symposium on Foundations of Computer Science, St. Louis, Missouri, October, 1990, pp. 503-513.

Halpern, Joseph, and Yoram Moses. "Knowledge and Common Knowledge in a Distributed Environment." *Journal of the Association for Computing Machinery* 37, no. 3 (July 1990): 549-587.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Synchronous networks
{{< tdclose >}}{{< tdopen >}}

Aguilera, Marcos Kawazoe, and Sam Toueg. "A Simple Bivalency Proof that *t*\-Resilient Consensus Requires *t*+1 Rounds." *Information Processing Letters* 71, nos. 3-4 (August 1999): 155-158.

Keidar, Idit, and Sergio Rajsbaum. "{{% resource_link "fd77e5b6-6a4a-47ce-b7b2-bfce8b40290c" "A Simple Proof of the Uniform Consensus Synchronous Lower Bound" %}}." *Information Processing Letters* 85, no. 1 (January 2003): 47-52.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Asynchronous networks
{{< tdclose >}}{{< tdopen >}}

Mattern, Friedemann. "Virtual Time and Global States of Distributed Systems." In *Parallel and Distributed Algorithms: Proceedings of the International Workshop on Parallel and Distributed Algorithms (Chateau de Bonas, Gers, France, October, 1988)*. Edited by Michel Cosnard, et al. Amsterdam, The Netherlands: North Holland, 1989, 215-226. ISBN: 9780444873675. Reprint, Yang, Zhonghua, and T. Anthony Marsland, eds. "Virtual Time and Global States of Distributed Systems." In *Global States and Time in Distributed Systems*. Los Alamitos, CA: IEEE Computer Society Press, 1994, pp. 123-133. ISBN: 9780818653001.

Fidge, Colin. "Logical Time in Distributed Computing Systems." *IEEE Computer* 24, no. 8 (August 1991): 28-33.

Chaudhuri, Soma. "More *Choices* Allow More *Faults*: Set Consensus Problems in Totally Asynchronous Systems." *Information and Computation* 105, no. 1 (July 1993): 132-158.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Asynchronous shared memory
{{< tdclose >}}{{< tdopen >}}

### Mutual exclusion

The following paper and thesis chapter present a new, fundamental lower bound for the time required to achieve mutual exclusion.

Fan, Rui, and Nancy Lynch. "An Ω*(n log n)* Lower Bound on the Cost of Mutual Exclusion." *Proceedings of the Twenty-Fifth Annual Symposium on Principles of Distributed Computing (PODC'06),* Denver, Colorado, (July 22-26, 2006). Best Student Paper Award.

Fan, Rui. "Mutual Exclusion." Chapter 4 in *Lower Bounds in Distributed Computing.* PhD dissertation, Department of Electrical Engineering and Computer Science, Massachusetts Institute of Technology, Cambridge, MA, February 2008.

### Wait-free computability and the wait-free consensus hierarchy

This paper popularized the notion of wait-free computability, and also introduced the wait-free consensus hierarchy.

Herlihy, Maurice. "Wait-Free Synchronization." *ACM Transactions on Programming Languages and Systems* 13, no. 1 (January 1991): 124-149.

This paper presents an interesting observation about the wait-free consensus hierarchy.

Jayanti, Prasad. "Robust Wait-Free Hierarchies." *Journal of the Association for Computing Machinery* 44, no. 4 (July 1997): 592-614.

### Wait-free vs. f-fault-tolerant data objects

Chandra, Tushar D., Vassos Hadzilacos, Prasad Jayanti, and Sam Toueg. "Generalized Irreducibility of Consensus and the Equivalence of *t*\-Resilient and Wait-Free Implementations of Consensus." *SIAM Journal on Computing* 34, no. 2 (2004): 333-357.

Borowsky, Elizabeth, Eli Gafni, Nancy Lynch, and Sergio Rajsbaum. "The BG Distributed Simulation Algorithm." *Distributed Computing* 14 (2001): 127-146.

Attie, Paul, Rachid Guerraoui, Petr Kouznetsov, Nancy Lynch, and Sergio Rajsbaum. "The Impossibility of Boosting Distributed Service Resilience." Submitted for journal publication, September 2009.

### Failure detectors, consensus, and set consensus

The idea of a "failure detector" was introduced in the following paper, which also shows how certain failure detectors can be used to solve consensus.

Chandra, Tushar Deepak, and Sam Toueg. "Unreliable Failure Detectors for Reliable Distributed Systems." *Journal of the Association for Computing Machinery* 43, no. 2 (March 1996): 225-267.

Lamport's "Paxos" paper solves consensus, essentially assuming an underlying failure detector service:

Lamport, Leslie. "The Part-Time Parliament." *ACM Transactions on Computer Systems* 16, no. 2 (May 1998): 133-169. Also available as Research Report 49, Digital Equipment Corporation Systems Research Center, Palo Alto, CA, September 1989.

The following paper proves that a certain failure detector is provably "weakest" for solving consensus:

Chandra, Tushar Deepak, Vassos Hadzilacos, and Sam Toueg. "The Weakest Failure Detector for Solving Consensus." *Journal of the Association for Computing Machinery* 43, no. 4 (July 1996): 685-722.

There are several new papers on failure detectors for set consensus, starting with this one:

Guerraoui, Rachid, Maurice Herlihy, Petr Kouznetsov, Nancy Lynch, and Calvin Newport. "On the Weakest Failure Detector Ever." *Distributed Computing* 21, no. 5 Special Issue (February 2009): 353-366.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Multiprocessor programming
{{< tdclose >}}{{< tdopen >}}

The brand-new Herlihy-Shavit textbook covers the principles of multiprocessor programming quite thoroughly:

Herlihy, Maurice, and Nir Shavit. *The Art of Multiprocessor Programming*. Burlington, MA: Morgan Kaufmann, 2008. ISBN: 9780123705914.

This paper introduced the MCS (Mellor-Crummey Scott) queue lock, which is fast, scalable and fair in a wide variety of multiprocessor systems.

Mellor-Crummey, John M., and Michael L. Scott. "Algorithms for Scalable Synchronization on Shared-Memory Multiprocessors." *ACM Transactions on Computer Systems* 9, no. 1 (February 1991): 21-65.

Magnussen, Peter, Anders Landin, and Erik Hagersten. "Queue Locks on Cache Coherent Multiprocessors." *Proceedings of the 8th International Symposium on Parallel Processing*, 1994, pp. 165-171.

The following monograph draft describes theoretical aspects of transactional memory.

Guerraoui, Rachid, and Michal Kapalka. *Transactional Memory: The Theory*. San Rafael, CA: Morgan and Claypool, 2010. ISBN: 9781608450114.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Self-stabilization
{{< tdclose >}}{{< tdopen >}}

Dijkstra's breakthrough paper originated the idea of distributed algorithm self-stabilization:

Dijkstra, Edsger W. "Self-Stabilizing Systems in Spite of Distributed Control." *Communications of the Association for Computing Machinery* 17, no. 11 (November 1974): 643-644.

The Dolev book contains everything you might want to know about basic self-stabilizing distributed algorithms:

![Buy at MIT Press](/images/mp_logo.gif) Dolev, Shlomi. *Self-Stabilization*. Cambridge, MA: MIT Press, 2000. ISBN: 9780262041782.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
Timed systems
{{< tdclose >}}{{< tdopen >}}

The Attiya-Welch book contains a chapter on basic clock synchronization algorithms:

Attiya, Hagit, and Jennifer Welch. *Distributed Computing: Fundamentals, Simulations, and Advanced Topics*. 2nd ed. New York, NY: Wiley-Interscience, 2004. ISBN: 9780471453246.

The following paper and thesis contain a lower bound on "gradient" clock synchronization. The thesis chapter is more up-to-date than the journal paper.

Fan, Rui, and Nancy Lynch. "Gradient Clock Synchronization." *Distributed Computing* 18, no. 4 (March 2006): 255-266.

Fan, Rui. "Gradient Clock Lower Bound." Chapter 2 in *Lower Bounds in Distributed Computing*. PhD dissertation, Department of Electrical Engineering and Computer Science, Massachusetts Institute of Technology, Cambridge, MA, February 2008.

The following monograph contains basic formal modeling and proof methods for timing-based systems. It provides the mathematical foundation for the Tempo toolset that we will use in this course.

Kaynar, Disun, Nancy Lynch, Roberto Segala, and Frits Vaandrager. *The Theory of Timed I/O Automata*. 2nd ed. San Rafael, CA: Morgan and Claypool, 2010. ISBN: 9781608450022.

{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}
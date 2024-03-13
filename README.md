# Local-first Resources

> A distributed system is one in which the failure of a computer you didn't even know existed can render your own computer unusable 
> -- <cite>Leslie Lamport (1987)</cite>

In local-first software, the availability of another computer should never prevent you from working.
- [Local-first software: You own your data, in spite of the cloud](https://www.inkandswitch.com/local-first/) 


### Blogs
- [Developing local-first software](https://electric-sql.com/blog/2023/02/09/developing-local-first-software)
- [Some notes on Local-First Development](https://bricolage.io/some-notes-on-local-first-development/)
- [What if we had Local-First Software?](https://adlrocha.substack.com/p/adlrocha-what-if-we-had-local-first)
- [Closing The Gap Between Your Users And Their Data](https://tripleodeon.com/2022/11/closing-the-gap-between-your-users-and-their-data)
- [In Search of a Local-First Database](https://jaredforsyth.com/posts/in-search-of-a-local-first-database/)
- [Building data-centric apps with a reactive relational database](https://riffle.systems/essays/prelude/)
- [Ready Player Two: Bringing Game-Style State Synchronization to the Web](https://rocicorp.dev/blog/ready-player-two)
- [A Graph-Based Firebase](https://stopa.io/post/296)

### Videos
- [Local-first software by Peter Van Hardenberg](https://www.youtube.com/watch?v=KrPsyr8Ig6M)
- [Automerge: Making Servers Optional for Real-Time Collaboration
by Martin Kleppmann](https://www.youtube.com/watch?v=GXJ0D2tfZCM)
- [CRDTs for Mortals by James Long](https://www.youtube.com/watch?v=DEcwa68f-jY)
- [Simplifying CRDTs for Local-First Software by Matt W](https://www.youtube.com/watch?v=AuQ02JopFso)
- [Local-first app development by Johannes Schickling](https://www.youtube.com/watch?v=qHSI5rxTp_Q)
- [The LoFi Movement: Building Local First Apps](https://www.youtube.com/watch?v=U1uhILa-wmI)
- [Real-time sync for web apps by Tuomas Artman](https://www.youtube.com/watch?v=WxK11RsLqp4&t=2175s)
- [Scaling the Linear Sync Engine by Tuomas Artman](https://www.youtube.com/watch?v=Wo2m3jaJixU)

## CRDTs
> A Conflict-free Replicated Data Type (CRDT) is a data structure that simplifies distributed data storage systems and multi-user applications. - [CRDT.tech](https://crdt.tech/)

### Papers
- [A comprehensive study of Convergent and Commutative Replicated Data Types](https://inria.hal.science/inria-00555588/)
- [Conflict-free Replicated Data Types: An Overview](https://arxiv.org/abs/1806.10254)
- [Approaches to Conflict-free Replicated Data Types](https://arxiv.org/abs/2310.18220)
- [Algebraic Replicated Data Types: Programming Secure Local-First Software](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ECOOP.2023.14)
- [LoRe: A Programming Model for Verifiably Safe Local-First Software](https://arxiv.org/abs/2304.07133)
- [VeriFx: Correct Replicated Data Types for the Masses](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ECOOP.2023.9)
- [Nested Pure Operation-Based CRDTs](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ECOOP.2023.2)
- [A Study of Semantics for CRDT-based Collaborative Spreadsheets](https://dl.acm.org/doi/10.1145/3578358.3591324)
- [Conflict-free Replicated Priority Queue: Design, Verification and Evaluation](https://dl.acm.org/doi/10.1145/3609437.3609452)

### Blogs
- [An Interactive Intro to CRDTs](https://jakelazaroff.com/words/an-interactive-intro-to-crdts/)
- [Designing Data Structures for Collaborative Apps](https://mattweidner.com/2022/02/10/collaborative-data-design.html)
- CRDT Survey by Matthew Weidner
    - [Part 1: Introduction](https://mattweidner.com/2023/09/26/crdt-survey-1.html)
    - [Part 2: Semantic Techniques](https://mattweidner.com/2023/09/26/crdt-survey-2.html)
    - [Part 3: Algorithmic Techniques](https://mattweidner.com/2023/09/26/crdt-survey-3.html)
    - [Part 4: Further Topics](https://mattweidner.com/2023/09/26/crdt-survey-4.html)
- [An introduction to Conflict-Free Replicated Data Types
](https://lars.hupel.info/topics/crdt/01-intro/)
- [Fuzz Testing RGA CRDT: Making sure collaborative text editing works correctly](https://jsonjoy.com/blog/fuzz-testing-rga-crdt)
- [List CRDT Benchmarks: 100x faster than state-of-art. Benchmarking json-joy against Automerge v2 and Y-libraries.](https://jsonjoy.com/blog/list-crdt-benchmarks)
- [I was wrong. CRDTs are the future](https://josephg.com/blog/crdts-are-the-future/)
- [A Look at Conflict-Free Replicated Data Types (CRDT)](https://medium.com/@istanbul_techie/a-look-at-conflict-free-replicated-data-types-crdt-221a5f629e7e)
- [A Gentle Introduction to CRDTs](https://vlcn.io/blog/intro-to-crdts)
- [You might not need a CRDT](https://driftingin.space/posts/you-might-not-need-a-crdt)
- [Towards a unified theory of Operational Transformation and CRDT](https://medium.com/@raphlinus/towards-a-unified-theory-of-operational-transformation-and-crdt-70485876f72f)

### Videos
- [Conflict Resolution for Eventual Consistency by Martin Kleppmann](https://www.youtube.com/watch?v=yCcWpzY8dIA)
- [CRDTs: The Hard Parts by Martin Kleppmann](https://www.youtube.com/watch?v=x7drE24geUw)
- [Practical Demystification of CRDT by Dmitry Ivanov & Nami Naserazad](https://www.youtube.com/watch?v=PQzNW8uQ_Y4)
- [Guaranteeing Consensus in Distributed Systems with CRDTs by Sun-Li Beatteay](https://www.youtube.com/watch?v=1Bs3Fj9rvks)
- [A CRDT Primer: Defanging Order Theory](https://www.youtube.com/watch?v=OOlnp2bZVRs)
- [CRDTs in Practice by Marc Shapiro & Nuno Preguiça](https://www.youtube.com/watch?v=xxjHC3yLDqw)
- [CRDTs Illustrated by Arnout Engelen](https://www.youtube.com/watch?v=9xFfOhasiOE)



## Conferences
- [Local-First Conf 2024](https://www.localfirstconf.com/)

## Podcasts & Newsletters
- [localfirst.fm: podcast about local-first software development](https://www.localfirst.fm/)
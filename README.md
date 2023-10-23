# curated-list-design

Online Resources:
1. Gergely Orosz's real world postmortems have great learnings - https://lnkd.in/grywMqKt
2. Neo K.'s System Design Newsletter makes engineering blogs more digestible - https://lnkd.in/gVnPv-Q8
3. Google Senior Staff (L7) Engineer's detailed whitepaper notes - https://lnkd.in/gGWf-Nvy
4. system-design-primer (hollistic resource for system design interviews) - https://lnkd.in/g6yMEsGv
5. ByteByteGo system design newsletter by Alex Xu - https://lnkd.in/gbCDC7XT
6. Architecture Notes - https://lnkd.in/grMHDuuE
7. Quastor System Design Case Studies - https://lnkd.in/g3bbCPHV
8. Level Up Coding's System Design Interview Survival Guide - https://lnkd.in/g8vKAbmD

Engineering Blogs:
1. Figma Engineering: https://lnkd.in/gFbvV8Mk
2. OpenAI Software Engineering: https://lnkd.in/g3wFsZk7
3. Engineering @ Meta: https://lnkd.in/gc9xnZQ8
4. Stripe Engineering: https://lnkd.in/g4JqgY39
5. Nextflix Tech: https://lnkd.in/gq-SWapT
6. Airbnb Tech: https://lnkd.in/gy3RF5ih
7. Uber Engineering: https://lnkd.in/gvga-NEg
8. Dropbox Tech: https://dropbox.tech/
9. Jane Street Tech Blog: https://lnkd.in/gRudhsrn
10. Engineering @ Ramp: https://lnkd.in/gw_kd2Vj
11. Instacart Tech: https://lnkd.in/gdGN9SrY
12. Paypal Tech: https://lnkd.in/gxj9Mx64
13. Rippling Engineering: https://lnkd.in/ge6K-UkG
14. Longer list https://lnkd.in/g3xqDpg6

Youtube Channels:
1. Martin Kleppman's channel - https://lnkd.in/gUJGHWEw
2. CMU Database Group - https://lnkd.in/gzTf2ZMs
3. MIT6.824: Distributed Systems - https://lnkd.in/gtmXKew7
4. DistSys Reading Group - https://lnkd.in/gdX7DQzq
5. TLA+ Video Course - https://lnkd.in/gUYB_FxX

Books:
1. Designing Data Intensive Systems by Martin Kleppman https://lnkd.in/gMhbvW23
2. Specifying Systems by Leslie Lamport - https://lnkd.in/gYzdwwBh
3. System Design Interview by Alex Xu - https://lnkd.in/gzUBcRe3
4. Database Internals by Alex Petrov - https://lnkd.in/gMC9B9UR
5. Building Microservices by Sam Newman - https://lnkd.in/gz5cwpG9

System Design:
1) Grokking System Design Fundamentals: https://lnkd.in/gtcCT-dJ
2) Grokking the System Design Interview: https://lnkd.in/giwyzfkT
3) Grokking Microservice Design Patterns - https://lnkd.in/gDMtPQxi


Tips:

1. **For a Read-Heavy System** - Consider using a Cache.
2. **For a Write-Heavy System** - Use Message Queues for async processing
3. **For a Low Latency Requirement** - Consider using a Cache and CDN.
4. **Need 𝐀tomicity, 𝐂onsistency, 𝐈solation, 𝐃urability Compliant DB** - Go for RDBMS/SQL Database.
5. **Have unstructured data** - Go for NoSQL Database.
6. **Have Complex Data (Videos, Images, Files)** - Go for Blob/Object storage.
7. **Complex Pre-computation** - Use Message Queue & Cache.
8. **High-Volume Data Search** - Consider search index, tries or search engine.
9. **Scaling SQL Database** - Implement Database Sharding.
10. **High Availability, Performance, & Throughput** - Use a Load Balancer.
11. **Global Data Delivery** - Consider using a CDN.
12. **Graph Data (data with nodes, edges, and relationships)** - Utilize Graph Database.
13. **Scaling Various Components** - Implement Horizontal Scaling.
14. **High-Performing Database Querie**s - Use Database Indexes.
15. **Bulk Job Processin**g - Consider Batch Processing & Message Queues.
16. **Server Load Management & Preventing DOS Attacks**- Use a Rate Limiter.
17. **Microservices Architecture** - Use an API Gateway.
18. **For Single Point of Failure** - Implement Redundancy.
19. **For Fault-Tolerance and Durability** - Implement Data Replication.
20. **For User-to-User fast communication** - Use Websockets.
21. **Failure Detection in Distributed Systems** - Implement a Heartbeat.
22. **Data Integrity** - Use Checksum Algorithm.
23. **Efficient Server Scaling** - Implement Consistent Hashing.
24. **Decentralized Data Transfer** - Consider Gossip Protocol.
25. **Location-Based Functionality** - Use Quadtree, Geohash, etc.
26. **Avoid Specific Technology Names** - Use generic terms.
27. **High Availability and Consistency Trade-Off** - Eventual Consistency.
28. **For IP resolution & Domain Name Query** - Mention DNS.
29. **Handling Large Data in Network Requests** - Implement Pagination.
30. **Cache Eviction Policy** - Preferred is LRU (Least Recently Used) Cache.
31. **To handle traffic spikes**: Implement Autoscaling to manage resources dynamically
32. **Need analytics and audit trails** - Consider using data lakes or append-only databases
33. **Handling Large-Scale Simultaneous Connections** - Use Connection Pooling and consider using Protobuf to minimize data payload

34 𝐇𝐨𝐰 𝐓𝐨 𝐇𝐚𝐯𝐞 𝐋𝐨𝐰 𝐋𝐚𝐭𝐞𝐧𝐜𝐲 𝐢𝐧 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐞𝐝 𝐒𝐲𝐬𝐭𝐞𝐦𝐬?

![image](https://github.com/programmers-for-programmers/curated-list-design/assets/4883000/48b64b1a-19c0-44ba-b2d9-6e6e50ef96cf)

35 𝐃𝐞𝐬𝐢𝐠𝐧 𝐏𝐚𝐭𝐭𝐞𝐫𝐧𝐬 𝐔𝐬𝐞𝐝 𝐀𝐜𝐫𝐨𝐬𝐬 𝐃𝐢𝐟𝐟𝐞𝐫𝐞𝐧𝐭 𝐋𝐚𝐲𝐞𝐫𝐬.

![image](https://github.com/programmers-for-programmers/curated-list-design/assets/4883000/bbffbb38-7260-4b5c-b885-a422e9d8bbd8)

36) **To prevent overloading system** - Use Token bucket and Leaky bucket algorithm
37) **Minimize deployment downtime** - Implement blue green deployment to minimize downtime and reduce risk
38) 5 𝐖𝐚𝐲𝐬 𝐭𝐨 𝐈𝐦𝐩𝐫𝐨𝐯𝐞 𝐘𝐨𝐮𝐫 𝐀𝐏𝐈 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞
![image](https://github.com/programmers-for-programmers/curated-list-design/assets/4883000/9110cb8b-9db4-4a73-9c9e-ba5fab770f77)


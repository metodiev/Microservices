# Microservices

# Microservices Interview Questions – Top 200

A curated list of the most commonly asked Microservices interview questions, ranging from beginner to advanced architecture and distributed systems topics.



# Table of Contents

1. Fundamentals
2. Architecture and Design
3. Communication
4. Data Management
5. Distributed Systems
6. Security
7. Scalability and Performance
8. Deployment and  DevOps
9. Observability
10. Resilience and Reliability
11. Testing
12. Event-Driven Architecture
13. Cloud & Kubernetes
14. Java & Spring Boot
15. Advanced & Difficult Questions



# 1. Fundamentals

1. What are microservices?
2. What problems do microservices solve?
3. Difference between monolith and microservices?
4. Advantages of microservices?
5. Disadvantages of microservices?
6. When should you NOT use microservices?
7. What are the characteristics of microservices?
8. What is a bounded context?
9. What is domain-driven design (DDD)?
10. What is loose coupling?
11. What is high cohesion?
12. What is service autonomy?
13. What is independent deployment?
14. What is decentralized governance?
15. What is decentralized data management?
16. What is Conway’s Law?
17. What is the strangler pattern?
18. What is service decomposition?
19. How do you identify service boundaries?
20. What is the difference between SOA and microservices?


# 2. Architecture and Design

21. What are design principles of microservices?
22. What is API-first design?
23. What is contract-first development?
24. What is a hexagonal architecture?
25. What is clean architecture?
26. What is CQRS?
27. What is event sourcing?
28. What is a sidecar pattern?
29. What is the ambassador pattern?
30. What is backend-for-frontend (BFF)?
31. What is API composition?
32. What is aggregation pattern?
33. What is database-per-service?
34. Shared database vs database-per-service?
35. What is anti-corruption layer?
36. What is transactional outbox pattern?
37. What is saga pattern?
38. Choreography vs orchestration?
39. What is service mesh?
40. What is API Gateway?


# 3. Communication

41. Synchronous vs asynchronous communication?
42. REST vs gRPC?
43. REST vs messaging?
44. What is idempotency?
45. What is eventual consistency?
46. What are HTTP status codes?
47. What is correlation ID?
48. What is request tracing?
49. What is service discovery?
50. Client-side vs server-side discovery?
51. What is load balancing?
52. What is message broker?
53. Kafka vs RabbitMQ?
54. What is backpressure?
55. What is retry mechanism?
56. What is exponential backoff?
57. What is dead-letter queue?
58. What is circuit breaker?
59. What is bulkhead pattern?
60. What is timeout management?



# 4. Data Management

61. How is data managed in microservices?
62. Why should each service own its database?
63. SQL vs NoSQL in microservices?
64. What is distributed transaction?
65. Why are distributed transactions difficult?
66. What is two-phase commit?
67. Why is 2PC avoided in microservices?
68. What is CAP theorem?
69. What is BASE consistency?
70. ACID vs BASE?
71. What is data replication?
72. What is sharding?
73. What is read replica?
74. What is cache-aside pattern?
75. What is distributed caching?
76. Redis use cases in microservices?
77. What is schema evolution?
78. What is data synchronization?
79. How do you handle schema migration?
80. How do you avoid data inconsistency?


# 5. Distributed Systems

81. What makes distributed systems hard?
82. What is network partition?
83. What is split-brain problem?
84. What is consensus?
85. What is leader election?
86. What is distributed locking?
87. What is clock skew?
88. What is distributed tracing?
89. What is service registry?
90. What is service heartbeat?
91. What is quorum?
92. What is eventual consistency in practice?
93. What are distributed failures?
94. What is failover?
95. What is graceful degradation?
96. What is chaos engineering?
97. What is the fallacies of distributed computing?
98. What is horizontal scaling?
99. What is vertical scaling?
100. How do microservices fail differently than monoliths?


# 6. Security

101. How do you secure microservices?
102. What is OAuth2?
103. What is OpenID Connect?
104. JWT vs session authentication?
105. What is mTLS?
106. What is zero trust architecture?
107. What is API security?
108. What is rate limiting?
109. What is API throttling?
110. What is RBAC?
111. What is ABAC?
112. How do services authenticate each other?
113. What is secret management?
114. What is Vault?
115. How do you secure Kafka?
116. What is token propagation?
117. What are common security vulnerabilities?
118. What is OWASP?
119. How do you secure communication channels?
120. What is certificate rotation?



# 7. Scalability and Performance

121. How do microservices scale?
122. Stateless vs stateful services?
123. What is autoscaling?
124. What is caching strategy?
125. What is connection pooling?
126. What is thread pool exhaustion?
127. What is reactive programming?
128. What is non-blocking I/O?
129. What is performance bottleneck analysis?
130. What is load shedding?
131. What is request batching?
132. What is asynchronous processing?
133. What is high throughput architecture?
134. What is low latency architecture?
135. What is memory leak in microservices?
136. How do you optimize startup time?
137. What is cold start problem?
138. How do you handle traffic spikes?
139. What are performance anti-patterns?
140. What metrics matter most?


# 8. Deployment and DevOps

141. What is CI/CD?
142. Blue-green deployment?
143. Canary deployment?
144. Rolling deployment?
145. What is immutable infrastructure?
146. What is Infrastructure as Code?
147. What is Docker?
148. Why are containers important?
149. What is Kubernetes?
150. What is Helm?
151. What is service orchestration?
152. What is configuration management?
153. What is feature toggle?
154. What is GitOps?
155. What is deployment rollback?
156. What is container orchestration?
157. What is init container?
158. What is sidecar container?
159. What is liveness probe?
160. What is readiness probe?



# 9. Observability

161. What is observability?
162. Logging vs monitoring vs tracing?
163. What is centralized logging?
164. What is distributed tracing?
165. What is OpenTelemetry?
166. What is Prometheus?
167. What is Grafana?
168. What are golden signals?
169. What are SLIs, SLOs, and SLAs?
170. What is alert fatigue?
171. What is structured logging?
172. What is log correlation?
173. What metrics should each service expose?
174. What is health check endpoint?
175. What is tracing propagation?
176. What is span?
177. What is trace sampling?
178. What is root cause analysis?
179. What is anomaly detection?
180. What are observability best practices?


# 10. Resilience and Reliability

181. How do you build resilient microservices?
182. What is retry storm?
183. What is cascading failure?
184. What is resilience testing?
185. What is fault tolerance?
186. What is disaster recovery?
187. What is multi-region deployment?
188. What is active-active architecture?
189. What is active-passive architecture?
190. What is self-healing infrastructure?



# 11. Testing

191. What types of testing are used in microservices?
192. What is contract testing?
193. What is consumer-driven contract testing?
194. What is integration testing?
195. What is end-to-end testing?
196. What is test container?
197. How do you mock dependencies?
198. What is chaos testing?
199. What is performance testing?
200. What is reliability testing?



# 12. Advanced and Difficult Questions

201. How would you migrate a monolith to microservices?
202. How do you debug production issues in distributed systems?
203. How do you handle cross-service transactions?
204. How do you prevent cascading failures?
205. How would you design a globally distributed system?
206. How do you achieve exactly-once processing?
207. How do you design idempotent APIs?
208. How do you handle versioning in APIs?
209. How would you design a payment system?
210. How would you design a high-scale notification system?
211. How would you design a real-time fraud detection platform?
212. How would you design microservices for banking systems?
213. How do you optimize Kafka for massive throughput?
214. How do you handle schema evolution in event-driven systems?
215. What are the biggest anti-patterns in microservices?
216. How do you handle distributed tracing at scale?
217. How do you ensure consistency across services?
218. How do you design multi-tenant microservices?
219. How do you reduce operational complexity?
220. What are the biggest lessons learned from production microservices?

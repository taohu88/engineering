# Designs
* [Netflix](https://www.youtube.com/watch?v=psQzyFfsUGU)
* [Tweet](https://www.youtube.com/watch?v=wYk0xPP_P_8)
# Protocol
* Http
* [XMPP](https://www.youtube.com/watch?v=gbeS8BwwM-M&list=PLQMs5svASiXPy6qdP8y0QyF6Vz1RXdQdN&index=2)
* [Gossip](https://www.youtube.com/watch?v=FuP1Fvrv6ZQ)
* [Gossip papers](https://paperswelove.org/2016/video/felix-lopez-introduction-to-gossip-protocols/)
# System overall
* Low level storage: Distributed File System
  * HDFS
  * GFS
* High level storage: No SQL
  * Key-value: redis, riak
  * Object: S3
  * Document: mongoDB, CounchDB
  * Column base: HBase, Cassandra
* High level storage: SQL
  * Oracle
  * MySQL
  * SQLServer
* Computation
  * MapReduce
* Cache
  * Consistent hashing
* Authentication (You are whom you claim to be)
  * [kerberos explained](https://www.youtube.com/watch?v=2WqZSZ5t0qk)
  * OpenID (Authentication)
* Authorization (Granting accesses)
  * [OAuth 2.0 and OpenID Connect](https://www.youtube.com/watch?v=996OiexHze0)
  * Frontend channel and backend channel
* Message queue
  * [Kafka](https://www.youtube.com/watch?v=UEg40Te8pnE)
* Logging
  * Logstash
  * [OpenTSDB](https://www.youtube.com/watch?v=gOJxLaz4hk8)  

# Encryption/Security
* [TLS](https://www.youtube.com/watch?v=VzWqnT5dErI)
* [CA](https://www.youtube.com/watch?v=heacxYUnFHA)

# ER
* [ER](https://www.youtube.com/watch?v=QpdhBUYk7Kk)

# Sites
* [HackerRank](https://www.hackerrank.com)
* LeetCode
* Project Euler

# Bi-directional communication (Http long polling and Websockets)
* Websockets is bi-directions
* Http is inherent uni-direction
* [Long polling vs websockets](https://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet)
* [Long polling vs websockets](https://stackoverflow.com/questions/12555043/my-understanding-of-http-polling-long-polling-http-streaming-and-websockets)
* [Bi directional courses](https://www.youtube.com/watch?v=RbQ9ZHzS6ag)
# Circuit breaking/Default response fallback/Request collapse
* [Hystrix](https://www.youtube.com/watch?v=0S59yCszYgg)
* Circuit breaking: Fail fast/exponential backoff retry/Isolating failure
* Default response: Fail gracefully
* Collapse requests
# Zookeeper
* Distributed config/synchronization
* [Helix](https://www.youtube.com/watch?v=mDZjM0CmxOE)
* Usa cases:
  * Distributed config
  * Group management
  * Leader election (app with lowest val)
  * Distributed locking and latches
* System on top of it
  * Curator
  * Exhibitor
# Leader election
* [The Paxos Algorithm](https://www.youtube.com/watch?v=d7nAGI_NZPk)
* Raft
* Zookeeper
* [Ring Leader Election Alg](https://www.youtube.com/watch?v=s0JCKUV-XXQ)
* [Bully alg](https://www.youtube.com/watch?v=xaISZOQ-PWY)

# Distributed lock
* [Using Distributed Locking to Build Reliable Systems](https://www.youtube.com/watch?v=MDuagr729aU)
* Ringpop
* Gossip alg
* Uber DLM example
  * Helix
  * Zookeeper
  
# Cluster management
* Helix

# Proxy
* [Reverse Proxy](https://en.wikipedia.org/wiki/Reverse_proxy)
* [nginx](https://www.nginx.com/resources/glossary/reverse-proxy-server/)

# Distributed Queue
* [Distributed Queue](https://www.youtube.com/watch?v=iJLL-KPqBpM&feature=youtu.be)

# Stories
* [How facebook prepare messager for new year eve](https://spectrum.ieee.org/tech-talk/computing/software/how-facebooks-software-engineers-prepare-messenger-for-new-years-eve)

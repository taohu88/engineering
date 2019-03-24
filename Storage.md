# Object Storage [S3](https://www.youtube.com/watch?v=VC0k-noNwOU)
* Use cases
  * Object
  * Object with version
  * Write Once and Read Many
  * Auto deletion: Lifecycle management
  * Auto archive
  * Static Website Hosting
* Authentication/Access control
  * Policy: Bucket, User
  * ACL: Coarse grained
  * IAM User
  * Group contains many users
  * Role
  * Bucket
* [Multi-Factor Authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication)
  * [Video](https://www.youtube.com/watch?v=07mRDyydCNY)
  * Knowledge: PIN/Secure Answer
  * Posession: Token/Phone
  * Inherent: FingerPrint/Iris/Face
  * Location: Company network
* Object Meta
  * Partition by prefix of key
  * Time: Creation/Access
  * Tags for business logic
* Version
  * Bucket level
  * Object level
  * Cross region replicated
* Storage classes
  * Standard (Durability 11 9s and 4 9s availability)
  * Reduced Redundancy (Durability 4 9s and 4 9s availability)
  * Glacier
  * Glacier Deep
  * Lifecycle management
    * auto archive
    * auto delete
* Encrption
  * Client: S3 Encryption Client
  * Server
    * SSE-S: Amazon
    * SSE-C: Client
    * SSE-KMS: AWS KMS
* Log
* Metrics
  * CloudWatch

# Distributed FS
* Use cases
  * Large files
* [HDFS](https://www.youtube.com/watch?v=GJYEsEEfjvk&t=616s)
  * Single NamedNode
  * DataNode
 * GFS
   * Single Master
   * Chunk Servers
   * Replicas
   * Master monitors Chunk Servers
   * Peroidical Replicas/Garbage clean
   * Lock is relative easier with single master
   * Master log for reconstruct state when failed

# Object Storage [S3](https://www.youtube.com/watch?v=VC0k-noNwOU)
* Use cases
  * Object
  * Object with version
  * Write Once and Read Many
  * Auto deletion: Lifecycle management
  * Auto archive
* Authentication/Access control
  * Policy: Bucket, User
  * ACL: Coarse grained
  * IAM User
  * Group contains many users
  * Role
  * Bucket
* [Multi-Factor Authentication](https://www.youtube.com/watch?v=07mRDyydCNY)
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
* [HDFS](https://www.youtube.com/watch?v=GJYEsEEfjvk&t=616s)
  * NamedNode
  * DataNode
 * GFS

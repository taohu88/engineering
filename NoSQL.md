# [NO SQL](https://www.youtube.com/watch?v=qI_g07C_Q5I)
# [BigTable](https://www.cs.rutgers.edu/~pxk/417/notes/content/bigtable.html)
* [Paper](http://static.googleusercontent.com/media/research.google.com/en/us/archive/bigtable-osdi06.pdf)
* Operations
  * Add data
    * Put
    * Increment
    * Append
    * Conditional updates
    * Bulk import
  * Read
    * Gets
    * Range scan
    * Filter
    * Full scan
    * Export
* Design pattern
  * Col promoted to row key
  * Wide col to deep table
* Design challenge
  * row key design is challenging
* Physical structure
  * Only save: Key -- Value
  * BigTable/STable/SSTable
  * SSTable
    * Index
    * BloomFilter
  * MTable
  * Log
* Logical view
  * (row key, col family:col qualify, timestamp) --> physical Key: value

# DynamoDB
* Partition Key
* Sort key
* Global sort key
* TTL

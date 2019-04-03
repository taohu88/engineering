# [AWS Lambda](https://www.youtube.com/watch?v=97q30JjEq9Y)
* Usages
  * Trigger
* Benefits
  * Code without worrying hardware
  * Lanaguages: java, python, node.js, c#, go
  * only charge for time it runs
* Concepts
  * Container
  
# MapReduce
* Use case
  * Process large data
* Steps
  * Input
    * Doc
  * Split
    * Split Doc
    * Map grabs == Split
  * Map
    * Word->Count
    * do the job
  * Shuffle
    * Same word
    * Reduce graps data == Shuffle
  * Reduce
    * Merge
    * Finalizer == Write
* Components
  * Master
  * Worker: Map and Reduce

# [Dispatch system: Ringpop](https://www.youtube.com/watch?v=OQyqJWQHp3g)
* Gossip: [SWIM gossip protocl](https://www.cs.cornell.edu/projects/Quicksilver/public_pdfs/SWIM.pdf)
* membership protocol
* consistent hash ring of its memebers
* forwarding as a convenience
* on the top of Node.js

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

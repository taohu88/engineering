# Basic Structures
* list (stack)
  * append, +, remove, pop, len
  * zip (think it as transpose)
* dict
  * items, get, []
* set
  * a & b, a ^ b, a - b
  * a.update([1,2,3], [4,5])
  * discard (no raise), remove (raise)
* tuple
  * no update
* defaultdict
  * defaultdict(int), defaultdict(list), defaultdict(lambda: 0)
* deque (FIFO queue/stack)
  * append/appendleft
  * pop/popleft
  * rotate(useful)
* Counter
  * Counter('abc'), Counter(a=1, b=2)
  * update (useful)
  * subtract
  * most_common (useful)
* OrderedDict
* nametuple (Be cautious, too hacky)

# Boolean check
* empty list --> false
* 0 --> false
* emtpy str --> false

# Class method, static method, property
* Class method: binding to class
* static method: not binding to class
* property: interface used as instance variable

# Iterator and Iterable
* Iterator
  * next --> ```__next__``` (magic method)
* Iterable
  * iter --> ```__iter__```
* StopIteration  

# Generator
* yield
* yield from
* return stop execution, but doesn't return result

# Exception
* raise Excetpion("Some things")
* try:
* except Exception as e:
* finally:

# Tips
* ipthon 
  * %%time

# Basic Structures
* list (stack)
  * append, +, remove, pop, len
  * zip
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

# Class method, static method, property
* Class method: binding to class
* static method: not binding to class
* property: interface used as instance variable

# Iterator and Iterable
* Iterator
  * __iter__ (magic method)

# Generator
* yield
* yield from
* return stop execution, but doesn't return result

# Exception
* raise Excetpion("Some things")
* catch (Exception as e):

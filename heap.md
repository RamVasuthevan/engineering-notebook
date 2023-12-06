### Heap

- Tree-based data structure that satisfies the heap property
- There are max heaps and min heaps
- Heap property for a max heap:
	- For any given node `C`, if `P` is a parent node of `C`, then the key (the value) of `P` >= the key of `C`
- Operations of a max heap:
	- Basic
		- `find-max` : find the max key
		- `push`: add a new key (aka `insert`)
		- `pop`: remove the max key from the heap and return it (aka `extract-max`) 
		- `replace`: pop root and push a new key. This is more efficient than a pop followed by a push because we only need to balance once instead of twice
	- Creation
		- `create`
		- `heapify`
		- `merge`
- Used to implement priority queues:
- Operations needed for a priority queue
	- `is_empty`
	- `insert_with_priority`
	- `pull_highest_priority_element`

  

See More:

- [Heap (data structure) - Wikipedia](https://en.wikipedia.org/wiki/Heap_(data_structure))
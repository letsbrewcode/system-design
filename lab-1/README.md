# System Design Lab #1

### Design a Tiny URL Service
Tiny URL is a URL shortening service where you can paste a long URL and it will generate small URL. Later this small URL can be used as the web address to access the long URL.
 - How would you design such a service?
 - What are key operations/APIs that you will provide and how will you implement them

### O(1) Search Data Structure
Design a data structure and algorithm that supports following:
 1. `append(item)`: Insert the `item` as the last element in data structure
 2. `get_latest()`: Retrives the newest `item` that was stored in the data structure
 3. `get_oldest()`: Retrives the oldest `item` that was stored in the data structure
 4. `search(item)`: Returns true if an `item` is present in the data structure
 5. `delete(item)`: Deletes the `item` if it is present in the data structure

All the operations have to be supported in `O(1)` time complexity.

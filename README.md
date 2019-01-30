# PagerReplacer

In an operating system that uses paging for memory management, 
a page replacement algorithm is needed to decide which page needs to be replaced when new page comes in.

## The code can implement three types of Page Replacement Algorithm

* First In First Out (FIFO)
  - In this algorithm, operating system keeps track of all pages in the memory in a queue, 
  oldest page is in the front of the queue. 
  When a page needs to be replaced page in the front of the queue is selected for removal.
  
* Optimal Page replacement
  - In this algorithm, pages are replaced which would not be used for the longest duration of time in the future.
  
* Least Recently Used
  - In this algorithm page will be replaced which is least recently used.
  
## Reference

* https://www.geeksforgeeks.org/page-replacement-algorithms-in-operating-systems/

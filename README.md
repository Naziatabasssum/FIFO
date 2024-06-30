# FIFO
1. Begin turning the pages.  
i) If the set can hold no more pages.  
a) Add pages one at a time into the collection until it is full or all requests for pages have been fulfilled.  
b) Maintain the pages in the queue simultaneously to carry out FIFO.  
b) Increased page error  
ii) Other  
Do nothing if the current page is included in the collection.  
If not, either a) the current page in the string should be substituted for the first page in the queue since it was the first to be placed into memory, or b) the first page in the queue should be removed.  
b) Add the currently viewing page to the queue.  
d) Page faults that increase.  
2. Return page errors.



Output:

Incoming  Frame 1  Frame 2  Frame 3
4                   4              -               - 
1                   4              1              -  
2                   4              1              2 
4                   4              1              2 
5                   5              1              2 
Total Page Faults: 4

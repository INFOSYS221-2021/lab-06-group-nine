# INFOSYS 221 lab 6

## Exercise 5.6.1
<p>
What is the type of collection used in the exercise? <br>
Queue

What are the different ways of iterating through a collection?<br>
While and for loops

How do you find out the size of a collection?<br>
_queue.qsize()_

How do you add an item to a collection? What happens if you try to add an item to a collection that is already full?<br>
Add item to a collection by doing _queue.put(item)_
Timeout error

How do you remove an item to a collection? What happens if you try to remove an item that does not exist in the collection?<br>
queue.get()
Timeout error

Change the implementation of a FIFO queue to a LIFO queue in 5.6.1.<br>
<code>
  import queue 

  Initialise a queue
  miqVoucherQ = queue.LifoQueue(maxsize = 100)
</code>
</p>
  
## Exercise 5.6.2
<p>
What is the type of collection used in the exercise?<br>
What are the different ways of iterating through a collection?<br>
How do you find out the size of a collection?<br>
How do you add an item to a collection? What happens if you try to add an item to a collection that is already full?<br>
How do you remove an item to a collection? What happens if you try to remove an item that does not exist in the collection?<br>
Change the implementation of a FIFO queue to a LIFO queue in 5.6.1.<br>
</p>

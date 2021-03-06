# JavaScript Algorithms and Data Structures
## BIG 0
O(n)
O = function
n - represents number of elements 

- O(1) = static amount of time 
- O(log n) - divide and conquer or binary search
- O(n) directly and linearly with N
- O(NlogN) = merge search
- O(n2) = checking two lists
- O(infinity) - flipping a coin 

Big O is the way we analyze how efficient algorithms (or code in this case) without getting too mired in the details.


## Stacks 
(last in, first out)
two principal operations:
- push(value), which adds an element to the collection, and
- pop(), which removes the most recently added element that was not yet removed.
- size() returns the size of the stack as an integer

## Queues 

FIFO (first in, first out)

- enqueued - adding int othe queue
- dequeued - removing from queue 
- size() - returns the size as an integer 


## Recursion 
A function calls itself

```js
//function template
var  myFunction = function() {
  if() {
  //base case 
  } else {
     //recursive case 
     myFunction();
  }
  return;
};
```

```js
//example function
var loopNtimes = function(n) {
   console.log("n equals" , n);
	if (n <= 1) {
	   console.log("done");
	   return "complete";
	}
	console.log(loopNtimes(n-1));
	return loopNtimes(n-1);
};


function a(foo) {
  if(foo >20) return foo;
  return b(foo+2);
}
```

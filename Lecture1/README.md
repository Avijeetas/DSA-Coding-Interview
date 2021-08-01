### What is Algorithm?
An algorithm is a set of step-by-step procedures, or a set of rules to follow, for completing a specific task or solving a particular problem.

### Some common algorithms
- Searching algorithms(Linear Search, Binary Search, Ternary Search etc.)
- Sorting algorithms(Bubble sort, insertion sort, Merge Sort, Heap sort etc)
- Graph algorithms(BFS, DFS, Dijkstra, Kruskal, Maxflow etc)

### What is Data Structure?
A data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data.
Data structures are implemented using algorithms.

#### List of common data structures
- Queue(First in first out)
- Stack (Last in first out)
- Priority Queue
- Deque(Doubly ended queue)
- Map 

### Complexity
The complexity of an algorithm is a function describing the efficiency of the algorithm in terms of the amount of data the algorithm must process


#### Time complexity
- A function 
- Describes the amount of time an algorithm takes in terms of the amount of input to the algorithm. 
- Time
	- the number of memory accesses performed
	- the number of comparisons between integers
	-  the number of times some inner loop is executed


#### Space Complexity
- A function
- Describes the amount of memory(space) an algorithm takes in terms of the amount of input to the algorithm.


For example, we might say "this algorithm takes n2 time," where n is the number of items in the input. Or we might say "this algorithm takes constant extra space," because the amount of extra memory needed doesn't vary with the number of items processed. 


#### Asymptotic Analysis
- handles such issues in analyzing algorithms
- We evaluate the performance of an algorithms in terms of input size
- The main idea of asymptotic analysis is to have a measure of the efficiency of algorithms that don’t depend on machine-specific constants and doesn’t require algorithms to be implemented and time taken by programs to be compared. 


#### Asymptotic Notations
- Asymptotic notations are mathematical tools to represent the time complexity of algorithms for asymptotic analysis

#### Worst, Average, Best Case

Let assume, we are given an array of list= [1,10,12,30, 59] and a target = 59 

Our job is to find the target value
```

int search(){
	for(int i=0;i<len(a);i++ )
	{
		if(a[i]==target)
			return i;
		
	}
	return -1;

}
```

return -1 denotes that the value is not present in the array.

**best case** 
- O(1) where the target is the first value of the array

**Worst case**
-	target would be either at the n-th position of the array or not present in the array . In that sense, the complexity would be O(N) where N is the number of operation[ size of the array]

**Average case**
- we take all possible inputs and calculate computing time for all of the inputs. Sum all the calculated values and divide the sum by total number of inputs.


[References]
- https://www.cs.utexas.edu/users/djimenez/utsa/cs1723/lecture2.html
- https://en.wikipedia.org/wiki/Data_structure
- https://www.geeksforgeeks.org/fundamentals-of-algorithms/

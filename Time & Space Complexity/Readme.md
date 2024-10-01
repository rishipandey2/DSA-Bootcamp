<h3>Prerequisites : <h3> 
<p>1- Limits<p>
<p>2- Logs<p>

# What is Time Complexity ? 
Ans - Time Complexity != Time taken<br>
Time Complexity is a Function that gives us the relationship about how the time will grow as the input grows.

# Why is Time Complexity Important ? 
Ans - Linear search = O(n)<br>
Binary Search = O(log n)<br>
Time Complexity of Binary Search is Better than Linear Search<br>

# What do we need to consider when thinking about Complexity?
Ans - 1 - Always look for the worst case time complexity.<br>
2 - Always look at complexity for large infinite data.<br>
3- We ignore all constants. <br>
4- Always ignore less dominating term.<br>
5- Order of Time Complexity - 0(1)< O(log n)< O(n) < O(2^n) <br>

# Big-Oh Notation ?
Ans - let's take an example O(N^3) - Here big Oh represent the upper bound <br>
The complexity will never exceed the N^3, it can be solved in less complexity<br>

# Big Omega Notation ? 
Ans - Omega represent lower bound, it means at least N^3 time, it can be solved in more complexity.<br>

# Theta Notation(What if an algo has upper and lower bound of N^2) ? 
Ans - Combining both lower and upper bound.<br>

# Little Oh Notation ?
Ans - THis also gives upper bound  but this is a strict upper bound.<br>
Big-O provides an upper bound on the function's growth, and it can include functions that grow at the same rate.<br>
Little-o is stricter and excludes the possibility of growing at the same rate; the function must grow strictly slower.<br>

# Little Omega Notation ? 
Ans - Little-omega notation, denoted as ω(f(n)), describes a strict lower bound on the growth rate of a function. It is the opposite of little-o notation.<br>


# What is Space Complexity?
Ans - Space Complexity of an algorithm is total space taken by the algorithm with respect to the input size. Space complexity includes both auxiliary space and space used by input.<br>

Auxiliary space is the extra space or temporary space used by an algorithm.


# Bankers-Algorithm-for-deadlock-Detection-in-C

The Banker algorithm, sometimes referred to as the detection algorithm, is a resource allocation and deadlock avoidance algorithm developed by Edsger Dijkstra that tests for safety by simulating the allocation of predetermined maximum possible amounts of all resources, and then makes an "s-state" check to test for possible deadlock conditions for all other pending activities, before deciding whether allocation should be allowed to continue.   
The algorithm was developed in the design process for the the operating system . 
When a new process enters a system, it must declare the maximum number of instances of each resource type that it may ever claim; clearly, that number may not exceed the total number of resources in the system. Also, when a process gets all its requested resources it must return them in a finite amount of time.
Banker's algorithm is a deadlock avoidance algorithm.
It is named so because this algorithm is used in banking systems to determine whether a loan can be granted or not.
Consider there are n account holders in a bank and the sum of the money in all of their accounts is S. Everytime a loan has to be granted by the bank, it subtracts the loan amount from the total money the bank has. Then it checks if that difference is greater than S. It is done because, only then, the bank would have enough money even if all the n account holders draw all their money at once.
Banker's algorithm works in a similar way in computers.
Whenever a new process is created, it must specify the maximum instances of each resource type that it needs, exactly.


Hence have sucessfully implemented the bankers algorithm for deadlock detection in C

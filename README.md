Download Link: https://assignmentchef.com/product/solved-csc-332-6x-operating-systems-cigarette-smokers-problem
<br>
<h2>Problem Description</h2>

Consider a system with 3 smoker processes and 1 agent process. Each smoker continuously rolls a cigarette and then smokes it. The smoker needs three ingredients: tobacco, paper, and matches. One of the smokers has paper, another has tobacco, and the third has matches. The agent has an infinite supply of all three materials and (randomly) places two of the ingredients on the table each time. The smoker who has the remaining ingredient then makes and smokes a cigarette, signaling the agent on completion. The agent then puts out another two of the three ingredients, and the cycle repeats.

<strong>TO DO </strong>Write a program to synchronize the agent and smoker processes using:

<ul>

 <li>semaphores</li>

 <li>pthread libraries</li>

</ul>

<h2>Instructions</h2>

<ul>

 <li>Please see this link for pseudocode: <a href="http://www.cs.umd.edu/~hollings/cs412/s96/synch/smokers.html">http://www.cs.umd.edu/~hollings/cs412/s96/synch/smokers</a>. <a href="http://www.cs.umd.edu/~hollings/cs412/s96/synch/smokers.html">html</a></li>

 <li>Though the description says the agent process can infinitely supply two of the three ingredients, you can assume that the agent places ingredients only a finite number of times, say for example 10.</li>

 <li>You need to use the sem.h header file in your semaphore-based solution.</li>

</ul>



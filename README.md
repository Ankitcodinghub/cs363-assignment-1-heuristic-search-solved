# cs363-assignment-1-heuristic-search-solved
**TO GET THIS SOLUTION VISIT:** [CS363 Assignment # 1-Heuristic Search Solved](https://www.ankitcodinghub.com/product/cs363-artificial-intelligence-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119006&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS363 Assignment # 1-Heuristic Search Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Programming Assignment # 1

Heuristic Search

Introduction

On page 103 of your textbook, you will find a diagram of the 8-puzzle. Your work for this assignment is to implement several search techniques to find the shortest path between the start state and the goal state.

Programming Assignment

Here is the goal state and four start states for the 8-puzzle.

Goal: Easy: Medium: Hard: Worst:

1 2 3 1 3 4 2 8 1 2 8 1 5 6 7

8 4 8 6 2 4 3 4 6 3 4 8

7 6 5 7 5 7 6 5 7 5 3 2 1

Implement the following search algorithms and test them on the start states and goal state shown above. Only A* needs to detect duplicate states and eliminate them from the remainder of the search.

1. A* search using the heuristic function f*(n) = g(n) + h*(n), where h*(n) is the number of tiles out of place (not counting the blank).

2. A* search using the Manhattan heuristic function.

3. Iterative deepening A* with the Manhattan heuristic function.

4. Depth-first Branch and Bound with the Manhattan heuristic function.

When defining the successor function, it is helpful to define the actions in terms of the empty tile, that is, the four actions are moving the empty tile right, down, left, and up. Consider the actions in this order in your implementation.

Problem Analysis:

For all the algorithms, include in your report a table the number of nodes expanded, the total time required to solve the puzzle, and the sequence of moves in the optimal solution. For Depth-first Branch and Bound, also record the time the optimal solution is found (typically not the same as the finish time).

Besides, answer the following questions:

1. What is the number of possible states of the board?

2. What is the average number of possible moves from a given position of the board?

4. Assuming the answer to question #2 is the “average branching factor” and a depth as in the answer to question #3, estimate the number of nodes that would have to be examined to find an answer by the brute force breadth-first search.

5. Assuming that your computer can examine one move per millisecond, would such a blind-search solution to the problem terminate before the end of the semester?

6. The “worst” example problem given above is actually one of the easiest for humans to solve. Why do you think that is the case? What lessons for AI programs are suggested by this difference between human performance and performance of your search program?

7. Compare A*, DFBnB, and IDA* and discuss their advantages and disadvantages.

Deliverables:

1) Well commented code;

2) A readme file explaining how to compile and run your code;

3) A written report explaining your experimental results and analysis.

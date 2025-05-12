# eecs2011-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [EECS2011 Assignment 3 Solved](https://www.ankitcodinghub.com/product/eecs2011-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91331&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS2011 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 1:

Draw an arithmetic expression tree that has four external nodes, storing the numbers 1, 5, 6, and 7 (with each number stored in a distinct external node, but not necessarily in this order), and has three internal nodes, each storing an operator from the set { +, –, *, / }, so that the value of the root is 21. Any of these operators may be used more than once, and they are real (not integer) operators, i.e., they may operate on and return fractions.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 2:

Let 𝑇 be a given binary tree with 𝑛 nodes. The distance between two nodes 𝑝 and 𝑞 in 𝑇 is the number of edges along the unique simple path between 𝑝 and 𝑞, i.e., 𝑑𝑝+ 𝑑𝑞 – 2𝑑𝑎, where 𝑎 is the lowest common ancestor (LCA) of 𝑝 and 𝑞, and 𝑑𝑥 denotes the depth of node 𝑥 in 𝑇. The diameter of 𝑇 is the maximum distance between two nodes in 𝑇 (i.e., the distance between the farthest pair of nodes in 𝑇). Give an efficient algorithm for computing the diameter of 𝑇 and analyze its running time.

[Note: Each node of T stores an element and a pair of references to its left and right children. Other than that, nodes of T do not have any additional space to store extra information, not even their depths. Also, you should not attempt to create a clone of T with extra spaces in the clone nodes. Hint: use a post-order traversal of T with strengthened post-condition. As an example, see how we use a composite Result type as the return type in the EulerTour algorithm , LS8, pp: 20-21.]

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Problem 3:

Tamarindo Airlines wants to give a first-class upgrade coupon to the top log 𝑛 of their frequent flyers, based on the number of miles accumulated, where 𝑛 is the number of the airlines’ frequent flyers. The algorithm they currently use, which runs in 𝑂(𝑛 log 𝑛) time, sorts the flyers by the number of miles flown and then scans the sorted list to pick the top log 𝑛 flyers. They have hired you as their chief software engineer.

Give an algorithm that identifies the top log 𝑛 flyers in 𝑂(𝑛) time.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Problem 4: Dynamic Median Finder (DMF):

We want to design a DMF ADT that maintains a collection of comparable elements and supports the following operations on the collection:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>insert(e):</li>
<li>getMed():</li>
<li>removeMed():</li>
</ul>
</div>
<div class="column">
inserts a given element 𝑒 in 𝑂(log 𝑛) time,

returns the median in 𝑂(1) time,

removes and returns the median in 𝑂(log 𝑛) time,

</div>
</div>
<div class="layoutArea">
<div class="column">
where 𝑛 denotes the current number of elements in the collection.

Give an implementation of the DMF ADT using two heaps as the only instance variables.

[The median of a collection of 𝑛 elements is the 𝑛/2 𝑡h smallest element (ties broken arbitrarily). For instance, the median of 4, 9, 1 is 4, the median of 9, 3, 3 is 3, the medianof 9,9,1,2 is 2,andthemedianof 17,-4,13,-7,13,15,5,2 is 5.]

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>

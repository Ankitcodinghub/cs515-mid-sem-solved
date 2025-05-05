# cs515-mid-sem-solved
**TO GET THIS SOLUTION VISIT:** [CS515 Mid Sem Solved](https://www.ankitcodinghub.com/product/cs515-mid-sem-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100709&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS515 Mid Sem Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Task 1: Creating the tree from the input data file

A binary search tree (BST) is to be constructed from the input (ip.txt) data file. Read the file, and create the BST using a pointer-based repreentation. Maintain links for left and right chlidren. The nodes of the tree are specified in level wise manner. Thus, root node and its children are mentioned first. In the subsequent lines, the child nodes are specified in left to right manner. All the key value of the node are unique and positive in nature. For each node, its key and the corresponding left and right child key values are provided. If left or right child is not available then it will be marked by -1.

After creating the tree, it is required to return the pointer to the root node. In all of the subsequent parts, this pointer should be passed as the tree, not the raw data from the file.

Let’s consider the contents of the sample input file is as below.

<pre>Filename: ip.txt
48 38 60
38 31 -1
60 56 -1
</pre>
<pre>31 15 34
56 -1 -1
15 -1 25
34 -1 -1
25 -1 -1
</pre>
<pre>The BST corresponding to this input file is as given below
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
48

38 60

31 56

34

After constructing the tree from the given input, check whether it is a valid BST or not. Also, print the preorder and inorder traversal of the constructed tree.

</div>
</div>
<div class="layoutArea">
<div class="column">
15

</div>
</div>
<div class="layoutArea">
<div class="column">
In this case,

<pre>the preorder traversal of the tree is 48 38 31 15 25 34 60 56
the inorder traversal of the tree is 15 25 31 34 38 48 56 60
</pre>
Task 2: Finding the farthest leaf node(s) of the tree

</div>
<div class="column">
Marks 40

</div>
</div>
<div class="layoutArea">
<div class="column">
In this task, you need to find the farthest leaf node(s) from the root in terms of number edges required to reach from the root to the leaf node.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<pre>For the aforementioned example, the farthest leaf node(s): 25
The distance of the leaf from the root is: 4
</pre>
Task 3: Finding the tree after performing right rotation

</div>
<div class="column">
Marks 30

</div>
</div>
<div class="layoutArea">
<div class="column">
Use the right rotation as shown in the following figure to perform rotation w.r.t. a node. Each rotation changes the root of the subtree at the position of rotation (the root changes from u to v for right rotation, according to the figure).

For performing the right rotation, we need to enter key value of the node. If right rotation can be performed then it performs the right rotation without violating BST property and prints the preorder and inorder traversal of the tree.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>For the aforementioned example,
Enter key value for right rotation: 15
Right rotation w.r.t 15 is not possible
</pre>
<pre>Enter key value for right rotation: 31
Right rotation w.r.t 31 is possible
The tree after right rotation
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
15

25

</div>
</div>
<div class="layoutArea">
<div class="column">
38

31

</div>
<div class="column">
48

56

34

</div>
<div class="column">
60

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>the preorder traversal of the tree is 48 38 15 31 25 34 60 56
the inorder traversal of the tree is 15 25 31 34 38 48 56 60
</pre>
Submission

</div>
<div class="column">
Marks 30

</div>
</div>
<div class="layoutArea">
<div class="column">
Mention any important points of your strategy and any other assumptions that you have used in the midsemREADME.txt file. Report the time complexity of your strategy with necessary justification. Also, mention if you have any specific restriction on your input and output. Submit the program using the following submission link only.

<pre>https://www.iitp.ac.in/~samrat/CompSysLab2_CS515/submission/
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Guidelines

<ol>
<li>a &nbsp;Do not use any library/package (eg. STL etc) to implement this. Your code must be well documented and any invalid input must also be handled properly.</li>
<li>b &nbsp;We will evaluate the codes using gcc or g++ commands at the terminal mode.</li>
<li>c &nbsp;There will be penalty if you are found to take any unfair means during the lab hours and during the assignment
submission process.
</li>
<li>d &nbsp;Copying others’ program and allowing others to copy your program will be equally penalized.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>

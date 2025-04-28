# comp3411-9814-artificial-intelligence-assignment-2---heuristics-search-learning-solved
**TO GET THIS SOLUTION VISIT:** [COMP3411/9814 Artificial Intelligence Assignment 2 – Heuristics, Search, Learning Solved](https://www.ankitcodinghub.com/product/comp3411-9814-artificial-intelligence-assignment-2-heuristics-search-learning-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;44612&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3411\/9814 Artificial Intelligence  Assignment 2 – Heuristics, Search, Learning Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<h1>Question 1: Search Algorithms for the 15-Puzzle</h1>
In this question you will construct a table showing the number of states expanded when the 15-puzzle is solved, from various starting positions, using four different searches:

<ul>
<li>Uniform Cost Search (with Dijkstra’s Algorithm)</li>
<li>Iterative Deepening Search</li>
<li>A<sup>*</sup>Search (using the Manhattan Distance heuristic)</li>
<li>Iterative Deepening A<sup>*</sup>Search</li>
</ul>
Go to the Course Web Site, Week 3 Prolog Code: Path Search, scroll to the Activity at the bottom of the page and click on “prolog search.zip”. Unzip the file and change directory to prolog search, e.g.

unzip prolog_search.zip cd prolog_search

Start prolog and load puzzle15.pl and ucsdijkstra.pl by typing

[puzzle15].

[ucsdijkstra].

Then invoke the search for the specified start10 position by typing

start10(Pos),solve(Pos,Sol,G,N),showsol(Sol).

When the answer comes back, just hit Enter/Return. This version of UCS uses Dijkstra’s algorithm which is memory efficient, but is designed to return only one answer. Note that the length of the path is returned as G, and the total number of states expanded during the search is returned as N.

<ol start="40">
<li>Draw up a table with four rows and five columns. Label the rows as UCS, IDS, A<sup>*</sup> and IDA<sup>*</sup>, and the columns as start10, start12, start20, start30 and Run each of the following algorithms on each of the 5 start states:</li>
</ol>
&nbsp;

(i)[ucsdijkstra]

(ii)[ideepsearch]

(iii)[astar]

(iv)[idastar]

In each case, record in your table the number of nodes generated during the search. If the algorithm runs out of memory, just write “Mem” in your table. If the code runs for five minutes without producing out- put, terminate the process by typing Control-C and then “a”, and write “Time” in your table. Note that you will need to re-start prolog each time you switch to a different search.

<ol>
<li>Briefly discuss the efficiency of these four algorithms (including both time and memory usage).</li>
</ol>
<h1>Question 2: Heuristic Path Search for 15-Puzzle</h1>
In this question you will be exploring an Iterative Deepening version of the Heuristic Path Search algorithm discussed in the Week 2 Tutorial. Draw up a table in the following format:

&nbsp;

<table width="445">
<tbody>
<tr>
<td width="65"></td>
<td colspan="2" width="119">start50</td>
<td colspan="2" width="127">start60</td>
<td colspan="2" width="134">start64</td>
</tr>
<tr>
<td width="65">IDA<sup>∗</sup></td>
<td width="40">50</td>
<td width="78">14642512</td>
<td width="40">60</td>
<td width="86">321252368</td>
<td width="40">64</td>
<td width="94">1209086782</td>
</tr>
<tr>
<td width="65">1.2 1.4

1.6
</td>
<td width="40"></td>
<td width="78"></td>
<td width="40"></td>
<td width="86"></td>
<td width="40"></td>
<td width="94"></td>
</tr>
<tr>
<td width="65">Greedy</td>
<td width="40"></td>
<td width="78"></td>
<td width="40"></td>
<td width="86"></td>
<td width="40"></td>
<td width="94"></td>
</tr>
</tbody>
</table>
The top row of the table has been filled in for you (to save you from running some rather long computations).

(a) Run [greedy] forstart50, start60 and start64, and record the values returned for G and N in the last row of your table (using the Manhattan Distance heuristic defined in puzzle15.pl).

(b)Now copy idastar.pl to a new file heuristic.pl and modify the code of this new file so that it uses an Iterative Deepening version of the Heuristic Path Search algorithm discussed in the Weak 2 Tutorial Exercise, with w = 1.2 .

In your submitted document, briefly show the section of code that was changed, and the replacement code.

(c) Run [heuristic] on start50, start60 and start64 and record the values of G and N in your table. Now modify your code so that the value of&nbsp; w is 1.4, 1.6 ;&nbsp; in each case, run the algorithm on the same three start states and record the values of G and N in your table.

(d)Briefly discuss the tradeoff between speed and quality of solution for these five algorithms.

<h1>Question 3: Decision trees</h1>
Consider the decision tree learning algorithm of Figure 7.7 and the data of Figure 7.1 from Poole &amp;Mackworth [1], also presented below. Suppose, for this question, the stopping criterion is that all of the examples have the same classification. The tree of Figure 7.6 was built by selecting a feature that gives the maximum information gain. This question considers what happens when a different feature is selected.

Figure 7.1: Examples of a user’s preferences

<ol>
<li>Suppose you change the algorithm to always select the first element of the list of features. What tree is found when the features are in the order [<em>Author, Thread, Length, WhereRead</em>]? Does this tree represent a different function than that found with the maximum information gain split? Explain.</li>
<li>What tree is found when the features are in the order [<em>WhereRead, Thread, Length, Author</em>]? Does this tree represent a different function than that found with the maximum information gain split or the one given for the preceding part? Explain.</li>
<li>Is there a tree that correctly classifies the training examples but represents a different function than those found by the preceding algorithms? If so, give it. If not, explain why.</li>
</ol>
<h1>Question 4: Decision trees</h1>
The goal is to take out-of-the-box models and apply them to a given dataset. The task is to analyse the data&nbsp; and&nbsp; build a model to predict whether income exceeds $50K/yr based on census data (also known as “Census Income” dataset).

Use the data set <strong>Adult Data Set</strong> from the Machine Learning repository [2]. Use the supervised learning methods discussed in the lectures, Decision Trees and&nbsp; Naive Bayes.

Do not code these methods: instead use the implementations from scikit-learn. Read the scikit-learn documentation on Decision Trees [3]&nbsp; and Naive Bayes [4], and the linked pages describing the parameters of the methods.

This question will&nbsp; help you master the workflow of model building. For example, you’ll get to practice how to use the critical steps:

<ul>
<li>Importing data</li>
<li>Cleaning data</li>
<li>Splitting it into train/test or cross-validation sets</li>
<li>Pre-processing</li>
<li>Transformations</li>
<li>Feature engineering</li>
</ul>
Use the sklearn documentation pages for instructions. You should need the classification algorithms.

There are also available Tutorials:

<ul>
<li>Sklearn – official tutorial for the sklearn package</li>
<li>Predicting wine quality with scikit-learn – Step-by-step tutorial for training a machine learning model</li>
</ul>
The data is available here:&nbsp; http://archive.ics.uci.edu/ml/machine-learning-databases/adult/

<strong>Preferences</strong>

<ol>
<li>Poole &amp;Mackworth, Artificial Intelligence: Foundations of Computational Agents, Chapter 7, Supervised Machine Learning)</li>
<li><a href="http://archive.ics.uci.edu/ml/datasets/Adult">http://archive.ics.uci.edu/ml/datasets/Adult</a><a href="http://archive.ics.uci.edu/ml/datasets/Adult">)</a>.</li>
<li><a href="https://scikit-learn.org/stable/modules/tree.html">https://scikit-learn.org/stable/modules/tree.html</a></li>
<li><a href="https://scikit-learn.org/stable/modules/naive_bayes.html">https://scikit-learn.org/stable/modules/naive_bayes.html</a></li>
</ol>
<h1>Submission</h1>
This assignment must be submitted electronically.

<strong>Put your zID and your name at the top of every page of your submission!</strong>

<strong>COMP3411 students</strong> should submit by typing <strong>give cs3411 hw2 … </strong>

(for example: give cs3411 hw2 assignment2.pdf)

<strong>COMP9814 students</strong> should submit by typing

<strong>give cs3411 hw2 … </strong>

(for example: give cs9414 hw2 assignment2.pdf)

The give script will accept *.pdf *.txt *.doc *.rtf

Late submissions will incur a penalty of 10% per day, applied to the maximum mark.

Group submissions will not be allowed. By all means, discuss the assignment with your fellow students. But you must write (or type) your answers individually. <strong>Do NOT copy anyone else’s assignment, or send your assignment to any other student. </strong>

Good luck!

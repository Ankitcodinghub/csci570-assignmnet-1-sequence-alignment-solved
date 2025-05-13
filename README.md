# csci570-assignmnet-1-sequence-alignment-solved
**TO GET THIS SOLUTION VISIT:** [CSCI570 Assignmnet 1-Sequence alignment Solved](https://www.ankitcodinghub.com/product/csci570-assignmnet-1-sequence-alignment-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93646&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI570 Assignmnet 1-Sequence alignment Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
The project is related to the implementation of the two different solutions discussed in Week 8 of the Lecture for the Sequence Alignment problem. You can work on this project in groups of no more than 3 people.

II. Project Description

Implement the basic Dynamic Programming solution to the Sequence Alignment problem. Run the test set provided and show your results.

A. Algorithm Description

Suppose we are given two strings 𝑋 and 𝑌, where 𝑋 consists of the sequence of

symbols 𝑥1, 𝑥2 , … , 𝑥𝑚 and 𝑌 consists of the sequence of symbols 𝑦1, 𝑦2 , … , 𝑦𝑛.

Consider the sets {1, 2, … , 𝑚} and {1, 2, … , 𝑛} as representing the different positions in the strings 𝑋 and 𝑌, and consider a matching of these sets; Recall that a matching is a set of ordered pairs with the property that each item occurs in at most one pair. We say that a matching 𝑀 of these two sets is an alignment if there are no “crossing” pairs: if (𝑖, 𝑗), (𝑖’, 𝑗’) ε 𝑀 and 𝑖 &lt; 𝑖’ , then 𝑗 &lt; 𝑗’. Intuitively, an alignment gives a way of lining up the two strings, by telling us which pairs of positions will be lined up with one another.

Our definition of similarity will be based on finding the optimal alignment between 𝑋 and 𝑌, according to the following criteria. Suppose 𝑀 is a given alignment between 𝑋 and 𝑌:

1. First, there is a parameter δ𝑒 &gt; 0 that defines a gap penalty. For each

position of 𝑋or 𝑌 that is not matched in 𝑀 — it is a gap — we incur a cost of δ.

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Second, for each pair of letters 𝑝, 𝑞 in our alphabet, there is a mismatch cost of α𝑝𝑞 for lining up 𝑝 with 𝑞. Thus, for each (𝑖, 𝑗) ε 𝑀, we pay the
appropriate mismatch cost α𝑥 𝑦 for lining up 𝑥𝑖 with 𝑦𝑗. One generally 𝑖𝑗

assumes that α𝑝𝑝 = 0 for each letter 𝑝—there is no mismatch cost to line up

a letter with another copy of itself—although this will not be necessary in

anything that follows.
</li>
<li>The cost of 𝑀 is the sum of its gap and mismatch costs, and we seek an
alignment of minimum cost.
</li>
</ol>
B. Input string Generator

The input to the program would be a text file containing the following information:

<ol>
<li>First base string (𝑠1)</li>
<li>Next 𝑗 lines consist of indices after which the copy of the previous string needs to be inserted in the cumulative string. (eg given below)</li>
<li>Second base string (𝑠2)</li>
<li>Next 𝑘 lines consist of indices after which the copy of the previous
string needs to be inserted in the cumulative string. (eg given below)
</li>
</ol>
This information would help generate 2 strings from the original 2 base strings. This file could be used as an input to your program and your program could use the base strings and the rules to generate the actual strings. Also note that the numbers 𝑗 and 𝑘 correspond to the first and the second string respectively. Make

sure you validate the length of the first and the second string to be 2𝑗 * 𝑙𝑒𝑛(𝑠1) and 2𝑘 * 𝑙𝑒𝑛(𝑠2). Please note that the base strings need not have to be of equal

length and similarly, 𝑗 need not be equal to 𝑘.

<pre>  ACTG
  3
  6
  1
  TACG
  1
</pre>
2 9

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Using the above numbers, the generated strings would be

ACACTGACTACTGACTGGTGACTACTGACTGG and TATTATACGCTATTATACGCGACGCGGACGCG

Following is the step by step process on how the above strings are generated.

<pre>  ACTG
  ACTGACTG
  ACTGACTACTGACTGG
  ACACTGACTACTGACTGGTGACTACTGACTGG
</pre>
<pre>  TACG
  TATACGCG
  TATTATACGCGACGCG
  TATTATACGCTATTATACGCGACGCGGACGCG
</pre>
C. Values for Delta and Alphas

Values for α’s are as follows. δ𝑒 is equal to 30.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
C

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
G

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
T

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
110

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
48

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
94

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
C

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
110

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
118

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
48

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
G

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
48

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
118

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
110

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
T

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
94

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
48

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
110

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
D. Programming/Scripting Languages

Following are the list of languages which could be used:

1. C

2. C++

3. Java

4. Python 5. Python3

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
E. Bounds

<ol>
<li>Basic Algorithm
0 &lt;= 𝑗, 𝑘 &lt;= 10

1 &lt;= 𝑙𝑒𝑛(𝑠1), 𝑙𝑒𝑛(𝑠2) &lt;= 2000

1 &lt;= 2𝑗 * 𝑙𝑒𝑛(𝑠1), 2𝑘 * 𝑙𝑒𝑛(𝑠2) &lt;= 2000
</li>
<li>Memory Efficient Algorithm
0 &lt;= 𝑗, 𝑘 &lt;= 20

1 &lt;= 𝑙𝑒𝑛(𝑠1), 𝑙𝑒𝑛(𝑠2) &lt;= 20000

1 &lt;= 2𝑗 * 𝑙𝑒𝑛(𝑠1), 2𝑘 * 𝑙𝑒𝑛(𝑠2) &lt;= 20000
</li>
</ol>
III. Goals

Following are the goals to achieve for your project

A. Your program should take 2 arguments

<ol>
<li>input file path</li>
<li>output file path (If path is valid and file not found, your program should create it)</li>
</ol>
Note: As mentioned in Part II-B input file will have data to generate strings. Since Gap penalty (δ𝑒) and Mismatch penalty (α𝑝𝑞) are FIXED, you have to hardcode

them in your program.

You are not allowed to use any libraries.

B. Implement the Dynamic Programming algorithm. Your program should print the following information at the respective lines in output file:

<ol>
<li>Cost of the alignment (Integer)</li>
<li>First string alignment ( Consists of A, C, T, G, _ (gap) characters)</li>
<li>Second string alignment ( Consists of A, C, T, G, _ (gap) characters )</li>
<li>Time in Milliseconds (Float)</li>
<li>Memory in Kilobytes (Float)</li>
</ol>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
`python2 basic_2.py input.txt output.txt` `java Basic input.txt output.txt` `python3 basic_3.py input.txt output.txt`

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Note: There can be multiple alignments which have the same cost. You can print ANY alignment generated by your program. The only condition is it should have a minimum cost.

e.g. For strings 𝑠1: A and 𝑠2: C, alignments A_, _C and _A, C_ both have alignment cost 60 which is minimum. You can print any one of them.

C. Implement the memory efficient version of this solution and repeat the tests in Part B.

D. Plot the results of Part B and Part C using a line graph

Please use the provided input files in the ‘datapoints’ folder for generating the data points to plot the graph.

<ol>
<li>Single plot of CPU time vs problem size for the two solutions.</li>
<li>Single plot of Memory usage vs problem size for the two solutions.</li>
</ol>
Units: CPU time – milliseconds, Memory in KB, problem size m+n

IV. Submission

A. You should submit the ZIP file containing the following files.

<ol>
<li>Basic algorithm file
Name of the program file should be ‘basic.c’ / ‘ basic.cpp’ / ‘Basic.java’ / ‘basic_2.py’ (Python 2.7) / ‘ basic_3.py’ (Python 3)
</li>
<li>Memory efficient algorithm file

Name of the program file should be ‘efficient.c’ / ‘efficient.cpp’ /

‘Efficient.java’ / ‘efficient_2.py’ (Python 2.7) / ‘efficient_3.py’ (Python 3)
</li>
<li>Summary.pdf
It must contain following details

<ol>
<li>datapoints output table (which are generated from provided input files)</li>
<li>Two graphs and Insights</li>
<li>Contribution from each group member e.g.coding, testing, report
preparation, etc if everybody did not have equal contribution
</li>
</ol>
(Please use the provided Summary.docx file, fill in the details and upload it as PDF)
</li>
<li>2 Shell files ‘basic.sh’ and ‘ efficient.sh’ with the commands to compile and run your basic and efficient version. These are needed to provide you flexibility in passing any additional compiler/run arguments that your programs might need. See More Hints (VII part E for more details)</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
basic.sh

Execution: ./basic.sh input.txt output.txt ./efficient.sh input.txt output.txt

B. The name of your zip file should have the USC IDs (not email ids) of everyone in your group separated by underscore. e.g.

– 1234567890_1234567890_1234567890.zip

– 1234567890_1234567890_1234567890

– basic_2.py

– efficient_2.py – Summary.pdf – basic.sh

– efficient.sh

V. Grading

Please read the following instructions to understand how your submission will be evaluated.

A. Correctness of algorithms – 70 points

<ol>
<li>Both programs (basic/ efficient) are correctly outputting file having all 5
lines in correct order: 15 points
</li>
<li>Basic Algorithm: 25 points</li>
<li>Memory Efficient Algorithm: 30 points</li>
</ol>
Note: Graders will execute your program on the `Linux` OS. The goal of Part A is to check correctness. The program should output valid alignment having minimum cost. Memory and Time will be evaluated in Part B.

B. Plots, analysis of results, insights and observations: 30 points

<ol>
<li>Your program will be run on the input files (provided by us in the ‘data
points’ folder) to generate output files. The memory and time in the output

files should be in “close range” to what is given by you in the Summary.pdf
</li>
<li>Correctness of the graph</li>
<li>Correctness of Analysis/ Insights</li>
</ol>
Note: Unlike Part A, evaluation of Part B is subjective so it will be done manually. So it is alright if your graphs/data points have ‘some’ outliers.

VI. What is provided to you in the zip file?

A. SampleTestCases folder containing sample input and output files

<ol start="2">
<li>Datapoint folder containing input files to generate graph data points.</li>
<li>Summary.docx file for reference</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>javac Basic.java
java Basic “$1” “$2”
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
VII. HINTS, NOTES, and FAQs

A. Regarding Input and string generation

<ol>
<li>We will never give an invalid input to your program. Input strings will always contain A, C, G, T only.</li>
<li>The length of the final input string should be equal to the
2𝑛𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑙𝑖𝑛𝑒𝑠 * 𝑙𝑒𝑛(𝑏𝑎𝑠𝑒 𝑠𝑡𝑟𝑖𝑛𝑔), as mentioned in the document.
</li>
<li>The string generation mechanism is the same irrespective of the basic or the
efficient version of the algorithm.
</li>
<li>The entire program (string generation, solution, write output) should be written in a single file. You may break those functions in different classes to make the code modular, but there should be only one file. Your program won’t be evaluated based on how modular it is.</li>
</ol>
B. Regarding Algorithm and output

<ol>
<li>DO NOT REFER TO THE PSEUDOCODE PROVIDED IN KLEINBERG AND
TARDOS
</li>
<li>DO NOT USE ANY LIBRARIES FOR WRITING YOUR ALGORITHMS.</li>
<li>Samples for time and memory calculation are provided. Please use them for
consistency.
</li>
<li>Your solutions for the regular and memory-efficient algorithms should be in two
different programs.
</li>
<li>There can be multiple valid sequences with the same optimal cost, you can output
any of those. All of them are valid.
</li>
<li>You should code both the basic version and memory-efficient algorithm. Even
though the memory-efficient version will pass all the bounds of the simple version, You must not use the memory-efficient version in both of the sub-problems.
</li>
<li>Your program should not print anything when it runs. It should only write to the output file.</li>
<li>There is no specific requirement for the precision of Time and Memory float values.</li>
<li>Time and Memory depend on so many factors such as CPU, Operating System, etc. So there might be differences in the output. Therefore, it will be evaluated subjectively. There must be a clear distinction in behavior between programs whose Time/ Memory complexity is O(n) vs O(n2) vs O(logn).</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
C. Regarding the plot

<ol>
<li>Both the graphs are line graphs. X-axis represents problem size as m+n, where m and n are lengths of the generated string and Y-axis of Memory plot represents memory in KB, and Y-axis of Time Plot represents time in milliseconds. The 2 lines in the graph will represent stats of basic and memory-efficient algorithms.</li>
<li>You can use any libraries/packages in any language to plot the graphs.</li>
<li>You do not have to provide code for generating the plots. Only add images in the
Summary.pdf
</li>
</ol>
</div>
</div>
</div>
</div>

Download Link: https://assignmentchef.com/product/solved-cosc6000-homework02
<br>
Suppose we have several student’s scores and we want to develop a program that calculate the average score.

Requirements:

User inputs score one by one.

The score is a positive or zero <strong>integer</strong> value.

When user inputs a <strong>negative value</strong>, the program calculates the mean score and is <strong>finalized</strong>. The mean score is <strong>rounded off to the first decimal place</strong>.

This task could be broken down into the following procedures:

<ol>

 <li>Initialize variables to store the number of student and the sum of score. (‘count=0’ and ‘sum=0’)</li>

 <li>Start a loop</li>

 <li>Get a student’s core. (cin &gt;&gt; score)</li>

 <li>If the core is negative, exit from the loop. (go to 8)</li>

 <li>Add the score to the sum. (sum += score)</li>

 <li>Increment the counter. (count++)</li>

 <li>Go back to 3</li>

 <li>Compute the mean score. (mean = sum / count)</li>

 <li>Print the result.</li>

 <li></li>

</ol>




<h1>Part 2</h1>

We develop “Buying Soda” code similarly with “Buying Pizza” code.  (See <strong><u>Sample</u></strong>) What size Soda is the best buy?

Which size gives the lowest cost per a little?

Soda sizes given in little.

Quantity of soda is based on the volume. Buying Soda Problem Defini on

Input:

Volume of two sizes of soda.

Cost of the same two sizes of soda.

https://tulane.instructure.com/courses/2165899/assignments/13460471           1/2 4/23/2018           Homework 02

Output:

Cost per a unit volume for each size of soda.

Which size is the best buy,

Based on lowest price per a unit volume,

If cost per a unit volume is the same, the smaller size will be the better buy.

Buying Soda Problem Analysis

Subtask 1

Get the input data for each size of soda

Subtask 2

Compute price per a unit volume for smaller soda

Subtask 3

Compute price per a unit volume for larger soda

Subtask 4

Determine which size is the better buy

Subtask 5

Output the results

* Declare and define a function to process Subtask 2 and 3.
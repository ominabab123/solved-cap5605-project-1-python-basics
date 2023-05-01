Download Link: https://assignmentchef.com/product/solved-cap5605-project-1-python-basics
<br>
5/5 - (1 vote)




Requirements:

<ol>

 <li>Create a class named State that will store information about a US state and provide methods to get, and set the data, and compare the states.

  <ol>

   <li>Data attributes: State Name, Capital City, State Abbreviation, State Population, Region, US House Seats</li>

   <li>Initializer (__init__)</li>

   <li>Getter and setter methods for each field</li>

   <li>__gt__ method so that two State objects can be compared based on state names</li>

   <li>__str__ method so that a state object can be printed like a string</li>

  </ol></li>

 <li>Create a program that will:

  <ol>

   <li>Read a file (csv) of states and create a list of state objects containing that data.</li>

   <li>Offer the user the following options:1) Print a state report2) Sort by state name (using Quick Sort)3) Sort by population (using Radix sort)4) Find and print a given state (using binary search if the data is sorted by statename, sequential search if not) 5) Quit</li>

   <li>Implement the given option, then prompt again. (deal with invalid choice)</li>

  </ol>Your program should have functions for options 1-5.</li>

</ol>

d. The State report in option 1 should be in this form:

State Name Capital City State Abbr State Population Region US House Seats ——————————————————————————————

Florida Tallahassee FL 19,552,860 Pennsylvania Harrisburg PA 12,773,801 Massachusetts Boston MA 6,692,824

e. The State report in option 5 should be in this form:

South 27

State Name: Capital City: State Abbr: State Population: Region:

<pre>US House Seats:</pre>

Florida Tallahassee FL 19,552,860 South27

Liu

University of North Florida

1

Middle Atlantic New England

18 9

CAP4630/5605 Project 1 – Python Basics

Provide docstring comments:

Comments for a module (must be at the top): ”””

<pre>Detailed description of the module.</pre>

Author: &lt;your name&gt;Version: &lt;date you last changed the class&gt; Email: &lt;your UNF email&gt;”””

Comments for a function definition (must be the first thing inside the function):

<pre>”””Description of the purpose of the function, the meaning of theinput parameters (if any) and the meaning of the return values(if any).:param  parameter  description of the parameter (one for each):return description of the return value:raise exceptions that may be raised in this function”””</pre>

Comments for a class definition (must be the first thing inside the class)

<pre>”””Detailed description of the class.”””</pre>

Liu University of North Florida 2

CAP4630/5605 Project 1 – Python Basics

Example Ouput:

CAP4640/5605 Project 1 Instructor: Xudong Liu

Enter the file name: States.csv There were 50 state records read.

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 1

State Name Capital City State Abbr State Population Region US House Seats ——————————————————————————————

Louisiana Wisconsin New Mexico …

Baton Rouge LA Madison WI Santa Fe NM

4,625,470 South 6 5,742,713 Midwest 8 2,085,287 Southwest 3

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 3States sorted by Population.

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 1

State Name Capital City State Abbr State Population Region US House Seats ——————————————————————————————

Wyoming Cheyenne WY Vermont Montpelier VT North Dakota Bismarck ND …

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 4

<pre>582,658626,630723,393</pre>

<pre>WestNew EnglandMidwest</pre>

1 1 1

Enter the state name: FloridaLiu University of North Florida

<pre>Sequential search</pre>

<pre>State Name:Capital City:State Abbr:State Population:Region:</pre>

<pre>US House Seats:</pre>

<pre>FloridaTallahasseeFL19,552,860South27</pre>

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 4Enter the state name: Canada

Sequential searchError: State Canada not found

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 2States sorted by State name.

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 1

State Name Capital City State Abbr State Population Region US House Seats ——————————————————————————————

Alabama Alaska Arizona …

Montgomery AL Juno AK Phoenix AZ

4,833,722 South 735,132 West 6,626,624 Southwest

7 1 9

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit

Enter your choice: 4Enter the state name: Kentucky

Liu University of North Florida




<pre>Binary search</pre>

<pre>State Name:Capital City:State Abbr:State Population:Region:</pre>

<pre>US House Seats:</pre>

<pre>KentuckyFrankfortKY4,395,295South</pre>

6

1. Print a state report2. Sort by State name3. Sort by Population4. Find and print a given state 5. Quit
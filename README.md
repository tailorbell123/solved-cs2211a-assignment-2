Download Link: https://assignmentchef.com/product/solved-cs2211a-assignment-2
<br>
<u>QUESTION 1</u> (25 marks)

Write a Bourne shell script <strong>lastarg</strong>, which takes 0 or more arguments and prints the last (rightmost) argument in the argument list. <strong><em>You can assume that arguments will be made up of letters and digits only</em>.  </strong>

Note that, the number of arguments <u>can be more than 10</u>. For example, the output of

<strong>lastarg arg1 arg2 arg3 arg4 arg5 arg6 arg7 arg8 arg9 arg10 arg11 </strong>

<strong> </strong>

should be

<strong>arg11 </strong>

If no argument is provided, simply return nothing.

<strong><em><u>You should write enough inline comments inside your shell script to explain each part of it.</u></em></strong>

<h1><em><u>In your report, you should include actual test cases (as well as sample outputs) to demonstrate all possible</u></em></h1>

<strong><em><u>options in your program.</u></em></strong>

<em>If </em><strong><em>lastarg</em></strong><em> is placed in your home directory, what will happen if you execute the following command?  Show the output and explain why you got this output. </em>

<strong>cd; lastarg .* </strong>

<strong> </strong>

<h2><u>QUESTION 2</u> (25 marks)</h2>

Write a Bourne shell script <strong>odd_prn</strong>, which echoes <strong><em><u>its shell script file name</u></em></strong> as well as <strong><em><u>the values of its odd</u> <u>arguments</u></em></strong>. Even arguments should be ignored. Each value should be echoed in a separate line. <strong><em>You can assume that arguments will be made up of letters and digits only</em>.</strong> Note that, the number or arguments can be even or odd. Note also that, the number of arguments <u>can be more than 10</u>. For example, the output of:

<strong>odd_prn to C or not to C that is the question  </strong>

should be

<strong>odd_prn  to  or  to  that  the  </strong>

If no argument is provided, simply return the shell script file name only.

<strong><em><u>You should write enough inline comments inside your shell script to explain each part of it.</u></em></strong>

<strong><em><u>In your report, you should include actual test cases (as well as sample outputs) to demonstrate all possible</u></em></strong><strong><em> <u>cases in your program.</u> </em></strong>

<em>If </em><strong><em>odd_prn</em></strong><em> is placed in your home directory, what will happen if you execute the following command?  Show the output and explain why you got this output. </em>

<strong>cd; odd_prn .* </strong>

<h2><u>QUESTION 3</u> (50 marks)</h2>

Draw a <strong><em>flow chart</em> </strong>and write a <strong><em>Bourne shell script</em></strong> that causes the following output (below) to be displayed.

Note that, there is a single space between each value.

<strong><em>The number of column should be taken as an <u>input during execution</u>.  </em></strong>

For example, if the input to the program is <strong>6</strong>, the program should produce the following output:

<h1>0</h1>

<strong>0 1  </strong>

<strong>0 1 2 </strong>

<strong>0 1 2 3 </strong>

<strong>0 1 2 3 4 </strong>

<strong>0 1 2 3 4 5  </strong>

<strong>0 1 2 3 4  </strong>

<strong>0 1 2 3  </strong>

<h1>0 1 2</h1>

<h1>0 1</h1>

<h1>0</h1>

<strong><em><u>You should write enough inline comments inside your shell script to explain each part of it.</u></em></strong>

<strong><em><u>In your report, you should include actual test cases (as well as sample outputs) to demonstrate all possible</u></em></strong><strong><em> <u>cases in your program.</u> </em></strong>

<strong> </strong>

<strong> </strong>
# csci112-lab-2--fibonacci-o-log-n-solved
**TO GET THIS SOLUTION VISIT:** [CSCI112  Lab 2- Fibonacci O(log n) Solved](https://www.ankitcodinghub.com/product/csci112-fibonacci-olog-n-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116920&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI112 &nbsp;Lab 2- Fibonacci O(log n) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
File names: Names of files, functions, and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

Documentation: Each file should begin with a docstring that includes your name, the class number and name, the lab number, and a short description of the lab, as well as documentation pertinent to that particular file.

Matrix: Write a Matrix class, in a module matrix.py. The initialization should take the number of rows and columns, and then an iterable of length rows * cols. It should implement at least the following methods:

• __init__

• __str__ • __mul__

• __pow__

Which should enable the following interactions:

&gt;&gt;&gt; from matrix import Matrix

&gt;&gt;&gt; m1 = Matrix(3, 4, range(3*4))

&gt;&gt;&gt; print(m1)

0 1 2 3

4 5 6 7

8 9 10 11

&gt;&gt;&gt; print(m1 * Matrix(4,3,range(4*3)))

42 48 54

114 136 158

186 224 262

&gt;&gt;&gt; m2 = Matrix(2, 2, [0,1,1,1])

&gt;&gt;&gt; print(m2)

0 1

1 1

&gt;&gt;&gt; print(m2 * m2)

1 1

1 2

&gt;&gt;&gt; print(m2 ** 2)

1 1

1 2

&gt;&gt;&gt; m3 = Matrix(2, 2, ’abcd’)

&gt;&gt;&gt; print(m3) a b c d

1

2

3

4

5

6

7

8

9 10

11

12

13

14

15

16

17

18

19

20

21

22

23

24

Recall that the product of a matrix A with entries aij and B with entries bij, when the number of columns in A is the same as the number of rows in B, is a matrix C with entries

cij = Xaikbkj

k

1

Make sure that exponentiation runs in O(logn) time.

Unit test: Implement a unit test module for your matrix class. Call the unit test module matrix_test.py.

Fibonacci: In a module named fibonacci.py, implement the Fibonacci function three different ways. One will execute in exponential time, O(2n), one in linear time, O(n), and one in log time O(logn). Mathematically, the fibonacci function is defined as

 0 if n = 0



f(n) = 1 if n = 1

 f(n− 1) + f(n− 2) otherwise

The log time algorithm should be based on calculating the powers of the matrix

Unit test: Implement a unit test module for your Fibonacci functions. Call the unit test module fibonacci_test.py.

Timing: Finally, implement a module called fibonacci_timing.py to test the runtime of your three fibonacci functions. Use the time.process_time_ns function to get more accurate timings, in nanoseconds. Design tests to show the different times of the different functions and illustrate the differences between O(2n), O(n), and O(logn).

Writeup: Write a short paper discussing your findings from the timing experiments, and why they support (or don’t!) our order of magnitude estimates of their runtimes.

This writeup must be in either a PDF or a LATEX document. LATEX is optional, but I highly recommend that you learn to use it as soon as possible. There are many online tutorials, and all of my lab notes and lectures are written in LATEX! A good place to get started in LATEX is https://www.overleaf.com/.

Put this writeup in a file called either lab02writeup.pdf or lab02writeup.tex

Turn in: Put the following files into a folder called csci112lab02yourname, zip it into a single compressed file and submit to canvas:

• matrix.py

• matrix_test.py

• fibonacci.py

• fibonacci_test.py

• fibonacci_timing.py

• Either:

– lab02writeup.tex

– lab02writeup.pdf

2

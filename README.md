# cse230-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [CSE230 Assignment 5 Solved](https://www.ankitcodinghub.com/product/cse230-assignment-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96169&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE230 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
You are required to turn in the following source file: assignment5.s

Objecves:

-write assembly language programs to:

-perform decision making using branch instructions.

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
-create loops

-use syscall operations to display integers and strings on the console window

-use syscall operations to read integers from the keyboard.

Assignment Description:

An array of integers can be assigned to a memory address in the .data section of a MIPS assembly language program as show below. Here the length of the array is stored first, and then the elements of the array numbers next.

Implement a MIPS assembly language program to perform the functionality of the following C program and print the updated array content, by listing each integer in it.

It should ask a user to enter three integers, an ending index, an integer, and another integer to use for a comparison. It should examine only the elements in the array located from the index 0 to the entered ending index to check if each of them is greater the smallest of the last two entered numbers and is less than the largest of the last two entered numbers, then if it is, then change each such element in the array within the range according to the calculation given in the C program umbers[j] = numbers[j]*num1 + num2. For instance, if a user enters 8, enters 3, then enters 23, then the output will be the following:

2 80 23 -7 68 -17 56 -4 23 -26 27

i.e., the numbers that are located between the index 0 and 7 are examined to see if each of them is greater than 3 and less than 23.

then each of such element is changed.

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
If your program causes an infinite loop, press Control and ‘C’ keys at the same time to stop it. Name your source code file assignment5.s.

<pre>                     .data
numbers_len:         .word     11
</pre>
<pre>numbers:             .word     2, 19, 23, -7, 15, -17,
11, -4, 23, -26, 27
</pre>
The following shows how it looks like in a C program:

int numbers_len = 11;

int numbers[11] = {2, 19, 23, -7, 15, -17, 11, -4, 23, -26, 27};

int endingIndex, num1, num2, temp; int j;

printf(“Enter an ending index:\n”);

//read an integer from a user input and store it in endingIndex scanf(“%d”, &amp;endingIndex);

printf(“Enter an integer:\n”);

//read an integer from a user input and store it in num1 scanf(“%d”, &amp;num1);

printf(“Enter another integer:\n”);

//read an integer from a user input and store it in num2 scanf(“%d”, &amp;num2);

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
//if num1 is larger than num2, swap them if (num1 &gt; num2)

{

temp = num1; num1 = num2; num2 = temp;

}

//At this point num1 will always be less or equals to num2

//changing the array content

for (j = 0; j &lt; endingIndex &amp;&amp; j &lt; numbers_len; j = j+1) {

if (numbers[j] &gt; num1 &amp;&amp; numbers[j] &lt; num2) {

numbers[j] = numbers[j]*num1 + num2; }

}

printf(“Result Array Content:\n”); for (j = 0; j &lt; numbers_len; j = j+1) {

printf(“%d\n”, numbers[j]); }

The following is a sample output (user input is in bold):

Enter an ending index:

8

Enter an integer:

3

Enter another integer:

23

Result Array Content: 2

80

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
23 -7 68 -17 56 -4 23 -26 27

————————————————– The following is another sample output:

————————————————–

Enter an ending index:

5

Enter an integer:

14

Enter another integer:

-2

Result Array Content: 10

19

23

-7 15 -17 11 -4 23 -26 27

————————————————–

</div>
</div>
</div>
</div>
</div>

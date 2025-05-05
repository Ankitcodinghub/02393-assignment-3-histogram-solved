# 02393-assignment-3-histogram-solved
**TO GET THIS SOLUTION VISIT:** [02393 Assignment 3-Histogram Solved](https://www.ankitcodinghub.com/product/02393-assignment-3-histogram-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101455&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;02393 Assignment 3-Histogram Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Histogram A histogram is a graphical way to display a distribution of a dataset into discrete intervals. Consider for instance a data set given by the numbers 100 95 47 88 86 92 75 89 81 70 55 80 and suppose we want build a histogram with 11 intervals [0 − 10), [10 − 19), . . . , [100 − 110) to be textually represented as

<pre>0: 0
10: 0
20: 0
30: 0
40: 1
50: 1
60: 0
70: 2
80: 5
90: 2
100: 1
</pre>
The task is to write a program that reads the following values (in this order) from the standard input (cin):

• the number l of intervals (e.g. 11 in the example) • the size n of the data set (e.g. 12 in the example) • and n non-negative integers.

and then outputs the histogram in the above format.

For simplicity, set the size k of the intervals to be the integer ⌈ml ⌉, where m is the maximum

number in the data set. That is, interval i should be [(i − 1) × k…i × k). Function ⌈·⌉ is implemented as function ceil() in library math.h

As an example, the input for the previous histogram is:

<pre>11 12 100 95 47 88 86 92 75 89 81 70 55 80
</pre>
and the output is as above, where one can see that k is ⌈100⌉ = ⌈9,0909…⌉ = 10, and thus the 11

i-th interval starts at (i−1)×10. For instance the last interval (11-th) starts at (11−1)×10 = 100. As another example: with the same data but interval size l = 7 we have the input

<pre>7 12 100 95 47 88 86 92 75 89 81 70 55 80
</pre>
and the output is:

<pre>0: 0
15: 0
30: 0
45: 2
60: 1
75: 6
90: 3
</pre>
where the size of the intervals is ⌈100⌉ = ⌈14,2857…⌉ = 15. 7

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The Maze In the lecture, we discussed the following piece of code typedef enum {wood , stone} material;

<pre>typedef struct{
  int x,y;
</pre>
bool isWall;

<pre>  material type;
}field;
</pre>
<pre>#define n 16
#define m 12
field playground[n][m];
</pre>
<pre>int main(){
  for (int i=0; i&lt;n; i++){
</pre>
<pre>    for (int j=0; j&lt;m; j++){
      playground[i][j].x=i;
      playground[i][j].y=j;
      playground[i][j].isWall=(i==0||i==(n-1)||(j==0&amp;&amp;i!=3) ||j==(m-1));
      if (playground[i][j].isWall &amp;&amp; !(i==3 &amp;&amp; j==0))
</pre>
<pre>        playground [i][j].type=stone;
      else
</pre>
<pre>        playground [i][j].type=wood;
    }
</pre>
} }

We want to make a mini text-based game out of this.

<ul>
<li>Define two global variables x and y that represent the position of a player in the playground,
and let’s have initially x = y = 5.
</li>
<li>Write a function that uses these global variables and displays the current situation on the standard output, writing a “*” for every field that is a wall, and a single space “ ” for every field that is empty, except the field that the player is on, that is denoted “O”. (The function may assume that the player is always within the playground.) Thus, the initial state is displayed as follows:
*** ************ ** ** ** ** *O* ** ** ** ** ** ****************
</li>
<li>Obtain a character from the standard input. If the character is “l”, then it means the player should make one step to the left if possible, i.e., if the field exists and is not a wall. If it is not possible, then the player remains in the same position. Similarly, we use characters “r” for right, “u” for up, and “d” for down. After each step, the playground is displayed again and the user can give the next command. The game ends when the user gives command “q”.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>

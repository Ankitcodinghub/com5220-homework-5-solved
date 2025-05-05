# com5220-homework-5-solved
**TO GET THIS SOLUTION VISIT:** [COM5220 Homework 5 Solved](https://www.ankitcodinghub.com/product/com5220-homework-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101903&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM5220 Homework 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Implement an adaptive interference cancellation system with the least mean squares (LMS) algorithm described in Chapter 4, the normalized LMS (NLMS) algorithm described in Chapter 5, or the variable-step LMS (VS-LMS) algorithm described in Chapter 5. The adaptive system is used to cancel interference, i(n) , contained in a primary signal d (n) , as depicted in Fig. 1. The primary signal serves as the desired signal for the adaptive system. The input signal is a filtered version of i(n) , i.e., x(n) = i(n)  h(n) , where  denotes the convolution operator.

primary signal d (n) = s(n) + i(n)

</div>
</div>
<div class="layoutArea">
<div class="column">
reference

input +

x(n) = i(n)h(n) –

</div>
<div class="column">


</div>
</div>
<div class="layoutArea">
<div class="column">
e(n) ◼ Figure 1 Adaptive interference canceling.

(1) For the LMS algorithm, the update equation is

fn+1 =fn +e(n)xn

</div>
</div>
<div class="layoutArea">
<div class="column">
where 

</div>
<div class="column">
is the step size,

</div>
<div class="column">
e(n) = d(n) − y(n) , and y(n) = fT x with nn

f=[f(0) f(1) f(L−1)]T nnnn

x =[x (0) x (1) x (L−1)]T nnnn

</div>
</div>
<div class="layoutArea">
<div class="column">
and L being the adaptive filter length.

<ol start="2">
<li>(2) &nbsp;For the NLMS algorithm, the update equation is
f =f + e(n)xn n+1 n c+xTnxn

where c is a small positive constant.
</li>
<li>(3) &nbsp;For the VS-LMS algorithm, the update equation is
fn+1 =fn +e(n)Mnxn where Mn is an LL diagonal matrix with
</li>
</ol>
Mn = diag{0(n),1(n),…,L−1(n)}. 1

</div>
</div>
<div class="layoutArea">
<div class="column">
Adaptive Processor

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
COM 5220 Adaptive Signal Processing Fall 2021

</div>
</div>
<div class="layoutArea">
<div class="column">
The i (n) ’s are adjusted according to the following rule:

For n=0, i(n)=max,i=0,1,…,L−1.

For n0, i(n)=i(n)c1 (with c1 1) if e(n)x(n−i) has N1 successive

sign changes and i(n)=i(n)c2 (with c2 1) if e(n)x(n−i) has no sign changes for N2 successive updates, where min  i (n)  max .

System Specifications:

⚫Assume f0 =0.

⚫Theinformationsignals(n)=1withP{s(n)=+1}=0.5and P{s(n)=−1}=0.5.

</div>
</div>
<div class="layoutArea">
<div class="column">
⚫ i(n) is generated from a uniformly distributed random variable with range ⚫ h(n) is a five-point impulse response, i.e., h(0) = 0.227 , h(1) = 0.46 ,

h(3) = 0.46 , and h(4) = 0.227 .

</div>
<div class="column">
[−1, 1] .

h(2) = 0.688 ,

</div>
</div>
<div class="layoutArea">
<div class="column">
⚫ The adaptive filter length is Parameter Settings:

</div>
<div class="column">
L = 6 .

</div>
</div>
<div class="layoutArea">
<div class="column">
⚫ For the LMS algorithm, 

⚫ For the NLMS algorithm, 

⚫For the VS-LMS algorithm, c1 =0.9, c2 =1.1, and N1 =N2 =3. Also, max

</div>
</div>
<div class="layoutArea">
<div class="column">
are determined by yourself.

</div>
</div>
<div class="layoutArea">
<div class="column">
is determined by yourself.

is determined by yourself and c = 10−3 .

</div>
</div>
<div class="layoutArea">
<div class="column">
Simulation Assignments:

Generate 12,000 samples for each test data, i.e., s(n) , i(n) , and x(n) , in each trial. The performance of each algorithm is examined by the bit error rate (BER) and the average squared error for different averaging intervals.

<ol>
<li>(1) &nbsp;Plot the learning curve, i.e., | e(n) |2 vs. the number of iterations for each algorithm. Note
that the learning curve is obtained by averaging the results over 100 trials.
</li>
<li>(2) &nbsp;Calculate BERs 1 and 2 of the adaptive system for different adaptive algorithms, where BER 1 is evaluated from iterations 101 to 12000 and BER 2 is from iterations 1001 to 12000 in each trial. The final BER for each case is obtained by averaging the results over</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
100 trials.

</div>
</div>
<div class="layoutArea">
<div class="column">
P (i)= 1 12000{sgn(e(n))s(n)}, i=1,2,…,100 

</div>
</div>
<div class="layoutArea">
<div class="column">
e1 12000−101 n=101 i

</div>
</div>
<div class="layoutArea">
<div class="column">
i  

</div>
</div>
<div class="layoutArea">
<div class="column">
and min

</div>
</div>
<div class="layoutArea">
<div class="column">
 1 P (i)=

</div>
<div class="column">
 {sgn(e(n))s(n)},i=1,2,…,100

</div>
</div>
<div class="layoutArea">
<div class="column">
 P (i); P =

</div>
</div>
<div class="layoutArea">
<div class="column">
e2 12000 −1001  1 100

</div>
<div class="column">
12000 n=1001

</div>
<div class="column">
ii

</div>
</div>
<div class="layoutArea">
<div class="column">
P =  e1

</div>
<div class="column">


</div>
<div class="column">
i=1

</div>
<div class="column">
e1

</div>
<div class="column">
e2

</div>
<div class="column">


</div>
<div class="column">
i=1

</div>
<div class="column">
e2  

</div>
</div>
<div class="layoutArea">
<div class="column">
 100

</div>
<div class="column">
100

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
1 100

</div>
<div class="column">
 P (i) 

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
COM 5220 Adaptive Signal Processing Fall 2021 (3)Calculate the average squared error of the adaptive system for different adaptive

algorithms. That is, calculate (1/ M) [s (n)−e (n)]2 in the ith trial, where M is the

n

averaging interval. The squared errors are averaged from iterations 101 to 12000 and from iterations 1001 to 12000, respectively, in each trial. The final average squared error for each case is obtained by averaging the results over 100 trials.

</div>
</div>
<div class="layoutArea">
<div class="column">
ii

</div>
</div>
<div class="layoutArea">
<div class="column">
e(i)= 1 12000[s(n)−e(n)]2, i=1,2,…,100 

</div>
</div>
<div class="layoutArea">
<div class="column">
 1 12000−101 n=101 

</div>
</div>
<div class="layoutArea">
<div class="column">


</div>
</div>
<div class="layoutArea">
<div class="column">
ii

</div>
</div>
<div class="layoutArea">
<div class="column">
 1 12000 2 

</div>
</div>
<div class="layoutArea">
<div class="column">


 1 100 1 100

</div>
</div>
<div class="layoutArea">
<div class="column">
e2(i)=12000−1001

</div>
<div class="column">
n=1001[s(n)−e(n)] , i=1,2,…,100 ii

</div>
</div>
<div class="layoutArea">
<div class="column">


1 i=1 i=1

from your simulation results?

(Note: Send your simulation results/answers along with the corresponding m-file(s) to the eeclass before 10:10 AM, Dec. 29, 2021.)

</div>
</div>
<div class="layoutArea">
<div class="column">
e = e (i); e =

</div>
<div class="column">


</div>
<div class="column">
2 

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
<div class="layoutArea">
<div class="column">
 100

(4) What conclusions can you make about performance comparisons of the three algorithms

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>

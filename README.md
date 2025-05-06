# mth373-573-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [MTH373-573 Homework 3 Solved](https://www.ankitcodinghub.com/product/mth373-573-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97991&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MTH373-573 Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Problem1: Newton’smethodin1dimension 30points

(a) Newton’s method for solving a scalar nonlinear equation 𝑓 (𝑥) = 0 requires computation of the derivative of 𝑓 at each iteration. Suppose that we instead replace the true derivative with a constant value 𝑑, that is, we use the iteration scheme:

𝑥𝑘+1 =𝑥𝑘 −𝑓(𝑥𝑘)/𝑑.

i) Under what conditions on the value of 𝑑 will this scheme be locally convergent? ii) What will be the convergence rate in general?

iii) Is there any value of 𝑑 that would still yield quadratic convergence?

(b) Write a Python function to implement Newton’s method in 1d. Your function should take as inputs the 1d function, its derivative, an initial guess and a tolerance for checking con- vergence. Use this function to find the roots of the following functions using Newton’s method with the provided initial guess.

i) 𝑥2 − 1 = 0, 𝑥0 = 106. ii) (𝑥−1)4 =0,𝑥0 =10. iii) 𝑥 − cos 𝑥 = 0, 𝑥0 = 1.

What is the observed convergence rate of Newton’s method for each problem? Why does each problem exhibit this convergence rate?

You can compute the rate by using the fact that the error at each iteration 𝑒𝑘 = 𝑥∗ − 𝑥𝑘 satisfies |𝑒𝑘+1| / |𝑒𝑘|𝑟 = 𝐶. Thus, |𝑒𝑘+1| / |𝑒𝑘|𝑟 = |𝑒𝑘| / |𝑒𝑘−1|𝑟 from which you should derive an equation for obtaining 𝑟 for each iteration. You can use the computed solution in the last iteration as the true solution 𝑥∗ and the last of these computed rates to be the rate of convergence.

</div>
</div>
<div class="layoutArea">
<div class="column">
Problem2: Newton’smethodforasystem

Consider the conversion formula from spherical to Cartesian coordinates:

𝑥 = 𝑟 sin 𝜃 cos 𝜑 𝑦 = 𝑟 sin 𝜃 sin 𝜑

</div>
<div class="column">
30points

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑧 = 𝑟 cos 𝜃

(a) Writeafunctionnewton(f,J,x0,tol=1e-12,maxit=500)thatimplementsNewton’s

method generically, with a starting guess of x0.

f is a function that accepts a numpy array 𝑥 of the current state and returns the function

value 𝑓 (𝑥) as another numpy array. Write f so that 𝑓 (𝑥) = 0 at the sought solution.

J is the Jacobian of f, so given a numpy array x, it returns a Jacobian matrix of the appropriate

</div>
</div>
<div class="layoutArea">
<div class="column">
2/6

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
dimensions.

Terminate the iteration once either the residual is smaller than tol or maxit iterations have been performed.

<ol start="2">
<li>(b) &nbsp;Write a function that, given 𝑥, 𝑦, and 𝑧, finds 𝑟, 𝜃 and 𝜑, using the Newton implementation from part (a). Do not reimplement Newton’s method, simply pass in appropriate functions f and J to newton from part (a).
Find a starting guess that leads to convergence in your experiments.

The routine should accept 𝑥, 𝑦, 𝑧 in one input vector and return 𝑟, 𝜃 and 𝜙 in one output vector.
</li>
<li>(c) &nbsp;Test your work from (a) and (b) by drawing 10 random vectors from 𝑥∗ ∈ R3 usingnp.random.randn and finding their spherical coordinates.
For each case, print the final relative residual ‖𝑥 − 𝑥∗‖2 / ‖𝑥∗‖2, where 𝑥 are the Cartesian coordinates corresponding to the spherical coordinates returned by your routine.

Also compare the polar coordinates 𝑤̃ = [𝑟̃ 𝜃̃ 𝜑̃]𝑇 output by your routine with the true values computed using the formulas:

𝑟 = √𝑥2 + 𝑦2 + 𝑧2 𝜃 = a r c c o s ( 𝑧𝑟 )

𝜑 = a r c t a n ( 𝑥𝑦 )

Let 𝑤 = [𝑟 𝜃 𝜑]𝑇 . For each example, print the relative error ‖𝑤 − 𝑤̃‖2 / ‖𝑤 ‖2 in your com-

puted values. Is this small whenever the residual is small? Why/why not?

H ints:

<ul>
<li>Read the documentation for and use np.arctan2 in implementing the formulas to find 𝑟, 𝜃, and 𝜙.</li>
<li>It is instructive to watch the conditioning of the Jacobian. A singular Jacobian will cause the method to break down or compute inaccurate results. Some starting guesses are more prone to this than others.
Problem3: Chebyshevpolynomials,Vandermondematrices50points

(a) A function 𝐹𝑛(𝑡) is known to satisfy the Chebyshev three-term recurrence if the following prop- erties hold:

𝐹0(𝑡) = 1

𝐹1(𝑡) = 𝑡
</li>
</ul>
</li>
</ol>
𝐹𝑛+1(𝑡) = 2𝑡𝐹𝑛(𝑡) − 𝐹𝑛−1(𝑡)

</div>
</div>
<div class="layoutArea">
<div class="column">
3/6

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Show that the function

satisfies the Chebyshev three-term recurrence.

H int: Remember the addition formula for cosines:

cos(𝛼 + 𝛽) = cos(𝛼) cos(𝛽) − sin(𝛼) sin(𝛽).

How would this apply to cos((𝑛 + 1) arccos(𝑡))?

<ol start="2">
<li>(b) &nbsp;Deduce that 𝐹𝑛(𝑡) is a polynomial. This is called the Chebyshev polynomial.</li>
<li>(c) &nbsp;The generalized Vandermonde matrix 𝑉 for a set of points 𝑥1,…,𝑥𝑛 with a set of functions 𝜙1,…,𝜙𝑛 is given by
𝑉𝑖𝑗 = 𝜙𝑗(𝑥𝑖).

Notice that this matrix captures an essential bit of interpolation: it maps coefficients with respect to the functions (𝜙𝑗) to point values at the points (𝑥𝑖):

∑𝛼𝑗𝜙𝑗(𝑥𝑖) = ∑𝑉𝑖𝑗𝛼𝑗 = (𝑉𝛼)𝑖.
</li>
</ol>
𝑗=1 𝑗=1

Clearly, 𝑉 −1 describes the reverse process, and the conditioning of 𝑉 can tell us quite a bit about how well-behaved of an operation interpolation is with respect to the given sets of functions and nodes.

Perform the following steps:

i) Construct 𝑛 × 𝑛 generalized Vandermonde matrices for 𝑛 = 5, 10, 15, … , 100.

ii) Plottheconditionnumberofthematrixwithrespectto𝑛.foreachofthecasesbelow: i. Equispaced nodes 𝑥𝑖 in the interval [−1, 1] (endpoints included), with the mono-

mials 𝜙𝑗(𝑥) = 𝑥𝑗.

ii. Chebyshev nodes in the range [−1, 1] are given by

𝑥𝑖 =cos(2𝑖+1𝜋), 2𝑛

with the monomials.

iii. Equispaced nodes 𝑥𝑖 in the interval [−1,1] (again, endpoint included), with the

Chebyshev polynomials 𝐹𝑗 .

iv. Chebyshev nodes in the interval [−1, 1] (see equation above) with the Chebyshev

polynomials 𝐹𝑗 .

Your output should include one (clearly labeled) plot as described above showing (and com-

paring) the behavior of the condition number for all four cases.

H int: Use matplotlib.pyplot.semilogy() to plot the values with a linear scale in 𝑛 on

the 𝑥 axis and a logarithmic scale for the condition number on the 𝑦 axis. 4/6

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐹𝑛(𝑡) = cos(𝑛 arccos(𝑡))

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
(d) Which of the combinations performs best?

</div>
</div>
<div class="layoutArea">
<div class="column">
Problem4: Interpolation,NewtonandCubicSpline 40 points (a) Thefollowingformulaiscalledthedivideddifferencesapproachtocomputingthecoefficients

of an interpolating polynomial using Newton’s polynomials as a basis:

𝑓[𝑡1,𝑡2,…,𝑡𝑘] ≔ 𝑓[𝑡2,𝑡3,…,𝑡𝑘] − 𝑓[𝑡1,𝑡2,…,𝑡𝑘−1] 𝑡𝑘 − 𝑡1

𝑓[𝑡𝑗] ≔ 𝑓(𝑡𝑗)

Prove that, using mathematical induction, that indeed this approach gives the coefficient of the 𝑗th basis function using the Newton interpolation polynomial.

<ol start="2">
<li>(b) &nbsp;Given the three data points (−1, 1), (0, 0), (1, 1), determine the interpolating polynomial of degree 2 (using hand calculations alone and showing all necessary steps) using:
i) Using the monomial basis. ii) Using the Lagrange basis.

iii) Using the Newton basis.

iv) Show that all three representations give the same polynomial.
</li>
<li>(c) &nbsp;Considerinterpolatingagivensetofdatapoints(𝑥𝑖,𝑦𝑖),𝑖=1,…,𝑛usingnaturalcubicsplines. Write a code to set up and solve the linear system that performs this interpolation. Plot the resulting cubic spline along with the data. For the data, pick 𝑛 = 6 random points (𝑥𝑖)𝑛𝑖=1 on [0, 1) with values (𝑦𝑖)𝑛𝑖=1 in [0, 1).
H int: Make sure you sort the 𝑥𝑖’s after you draw the random numbers and before you start constructing the spline, to avoid confusing your spline construction code.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5/6

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Submission Notes

<ol>
<li>Theanswertoalltheoreticalproblems,outputofPythoncodeforcomputationalproblems including figures, tables and accompanying analyses should be provided in a single PDF file along with all your code files.</li>
<li>Youcantypeset(pleaseconsiderusingLATEXifyouchoosetodoso),orwritebyhandand scan/take photographs of solutions for theoretical questions. For scanning or photography, please put in the extra effort and provide a single PDF file of your submission.</li>
<li>For Problem 2, submit your code in one file: problem_2.py. You can use the Python file provided as a boilerplate.</li>
<li>For Problem 3, submit your code in one file again: problem_3.py. You will of course, copy- paste the functions written in problem_2.py for Gaussian elimination without and with partial pivoting into this file.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
6/6

</div>
</div>
</div>

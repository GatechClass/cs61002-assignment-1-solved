# cs61002-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS61002 Assignment 1 Solved](https://mantutor.com/product/cs610-general-policies-solved-6/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114025&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61002 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
• You should do this assignment alone.

• Do not copy or turn in solutions from other sources. You will be penalized if caught.

Submission

• Submission will be through Canvas.

• Submit a compressed file called “⟨roll⟩-assign1.tar.gz”. The compressed file should have the following structure.

— roll

— — roll-assign1.pdf

— — &lt;problem4-dir&gt;

— — — &lt;source-files&gt;

The PDF file should contain solutions for the first three problems, and your description and results for the fourth problem. Show your computations where feasible and justify briefly.

• We encourage you to use the LATEX typesetting system for generating the PDF file. You can use tools like Tikz, Inkscape, or Draw.io for drawing figures if required. You can alternatively upload a scanned copy of a handwritten solution, but make sure the submission is legible.

• You will get up to two late days to submit your assignment, with a 25% penalty for each day.

Consider the following loop.

float s = 0.0, A[size]; int i, it, stride; for (it = 0; it &lt; 1000 * stride; it++) { for (i = 0; i &lt; size; i += stride) { s += A[i];

}

}

1

2

3

4

5

6

7

Assume an 8-way set-associative cache with a capacity of 256 KB, line size of 64 B, and word size of 4 B (for float). The cache is empty before execution and uses an LRU replacement policy. Given size=32K, determine the total number of cache misses on A for the following access strides: 1, 4, 16, 64, 2K, 8K, 16K, and 32K. Consider all the three kinds of misses: cold, capacity, and conflict.

Consider a cache of size 64K words and lines of size 8 words. The matrix dimensions are 1024×1024. Perform cache miss analysis for the kij and the jik forms of matrix multiplication (shown below) considering direct-mapped and fully associative caches. The arrays are stored in row-major order. To simplify the analysis, ignore misses from cross-interference between elements of different arrays (i.e., perform the analysis for each array, ignoring accesses to the other arrays). Listing 1: kij form

for (k = 0; k &lt; N; k++)

for (i = 0; i &lt; N; i++)

for (j = 0; j &lt; N; j++)

C[i][j] += A[i][k] * B[k][j];

1

2

3

4

Listing 2: jik form

for (j = 0; j &lt; N; j++)

for (i = 0; i &lt; N; i++)

for (k = 0; k &lt; N; k++)

C[i][j] += A[i][k] * B[k][j];

1

2

3

4

Your solution should have a table to summarize the total cache miss analysis for each loop nest variant and cache configuration, so there will be four tables in all. Justify your computations.

Consider the following code.

#define N (4096) double y[N], X[N][N], A[N][N]; for (k = 0; k &lt; N; k++)

for (j = 0; j &lt; N; j++)

for (i = 0; i &lt; N; i++)

y[i] = y[i] + A[i][j] * X[k][j];

1

2

3

4

5

6

Assume a direct-mapped cache of capacity 16 MB, with 32 B cache lines and a word of 8 B. Assume that there is negligible interference between the arrays A, X, and y (i.e., each array has its 16 MB cache for this question), and arrays are laid out in the row-major form.

Estimate the total number of cache misses for A, X, and y.

Assume a naïve O(n3) sequential matrix multiplication kernel (ijk form) for matrices of dimensions 4096×4096 (given).

(i) Implement an optimized version of the sequential matrix multiplication implementation using loop blocking. Experiment with different block dimensions (for e.g., 4×4 to 32×32).

Use a table to report the speedup of your optimized implementation over the sequential implementation for the different block sizes that you have tried. The first three columns will be the block sizes for matrices A, B, and C, and the last column will report the speedup compared to the sequential version.

(ii) Note the block size that works best for your setup. Remember that the cache hierarchy will influence the optimal block dimensions. Justify the improved performance by tracking performance counters with PAPI. List the PAPI version and the performance counters you have used.

• Do not change the ijk loop order.

• Create separate functions for your optimized variants for ease of debugging and evaluation.

• You should time your code on a noiseless system (i.e., no concurrent applications are running). Take times for 3–5 runs, and use the arithmetic mean.

• Report the cache hierarchy for the system you will use.

• Ensure that you are using relatively recent versions of PAPI (v5.7+).

• We will try to reproduce your results.

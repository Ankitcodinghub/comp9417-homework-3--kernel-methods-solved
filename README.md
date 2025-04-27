# comp9417-homework-3--kernel-methods-solved
**TO GET THIS SOLUTION VISIT:** [COMP9417 Homework 3- Kernel Methods Solved](https://www.ankitcodinghub.com/product/comp9417-machine-learning-tutorial-kernel-methods-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124059&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9417 Homework 3- Kernel Methods Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
Question 1 (Dual Perceptron)

Question 2 (Feature Transformations)

Recall that the XOR function (graphed below) is not linearly separable. Show how we can learn the XOR function using a linear classifier after applying a feature transformation to the original dataset. As a concrete example, show how to extend the Dual Perceptron from the previous question to learn the XOR function.

Figure 1: XOR function

Question 3. (The Kernel Trick)

Using the context of the previous question, discuss the computational issues that arise from having to compute high dimensional feature transformations. Show how these can be mitigated by using the Kernel trick, and use this to extend the dual perceptron learning to kernel perceptron learning.

Question 4. (Kernels and their Feature Representations)

In this question, we will show how the choice of kernel gives us different feature transformations. Note

1

that in practice, we will simply choose a kernel and not be too concerned with the exact feature transformation, but it is important to know that different kernels correspond to different representations. (a) Let x,y ∈ R2 (i.e. x and y are two dimensional vectors), and consider the kernel

k(x,y) = (2hx,yi + 3)3.

Compute the feature vector φ(x) correpsonding to this kernel. (In other words, the feature representation of x and y such that hφ(x),φ(y)i = k(x,y))

(b) Challenge: Let x,y ∈ R, and consider the Gaussian kernel:

.

Hint: Use a Taylor expansion to rewrite the exponential in terms of a summation.

Question 5 (More of the Kernel Trick)

You are told that the “kernel trick” means that a non-linear mapping can be realised from the original data representation to a new, implicit feature space simply by defining a kernel function on dot products of pairs of instances from the original data. To see why this is so, you take two instances x = [1,2]T and y = [3,2]T, and take their dot product hx,yi and obtain the answer 7. Clearly, raising this dot product to the power of two will give (hx,yi)2 = 49. Now expand out this expression to show that this is the same answer you would have obtained if you had simply done a set of feature transformations on the original data.

Question 6 (More Feature Transformations)

Consider the following depiction of a feature transformation from two dimensional space (R2) to three dimensional space (R3). Why would we use such a transformation? Generate one example from the ◦ class in the original space, and another example from the × class in the original space, and show their transformed values in the new space.

Question 7 (Support Vector Machines)

The Support Vector Machine is a essentially an approach to learning linear classifiers, but uses a alternative objective function to methods we looked at before, namely maximising the margin. Learning

Page 2

algorithms for this problem typically use quadratic optimization solvers, but it is possible to derive the solution manually for a small number of support vectors.

Here is a toy data set of three examples shown as the matrix X, of which the first two are classified as positive and the third as negative, shown as the vector y. Start by constructing the Gram matrix for this data, incorporating the class labels, i.e., form the matrix X0(X0)T. Then solve to find the support vectors, their Lagrange multipliers α, then determine the weight vector w, threshold t and the margin m.

X y X

1. Set up the Gram matrix for labelled data

2. Set up the expression to be minimised

3. Take partial derivatives

4. Set to zero and solve for each multiplier

5. Solve for w

6. Solve for t

7. Solve for m

Page 3

# cse472-assignment-2-gaussian-mixture-model-gmm-solved
**TO GET THIS SOLUTION VISIT:** [CSE472 Assignment 2-Gaussian Mixture Model (GMM) Solved](https://www.ankitcodinghub.com/product/cse472-assignment-2-gaussian-mixture-model-gmm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96557&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE472 Assignment 2-Gaussian Mixture Model (GMM) Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assignment 2: Expectation-Maximization Algorithm for Gaussian Mixture Model

<strong>Description of the Assignment</strong>

Let’s assume you have been hired by Bangladesh Navy as a data analyst for their newly acquired Ming-class submarines. They are planning to use these submarines to secure national maritime border. One of their potential targets is pirate ship. They use active acoustic sonar to find floating ships. By transmitting a sound pulse and receiving the echo on an array, the sonars can determine the direction of the echoes that return from objects hit by the sound. They can also measure the time it takes for echoes to return and calculate the distance to the object causing the echo. Unfortunately, if there are several ships nearby, the signals cause interference. Using periscope visuals, it is possible to determine the number of ships but exact location of each ship is difficult to locate. Without precise location, a torpedo hit is not guaranteed. The 2D plot of a sample sonar data is given in Figure 1. There are three ships in surface water, one inside each black circle. Each blue dot represents a single location measurement of one of the three ships. You have been instructed to build a system which takes the sonar data as well as the number of ships as input and provide the estimated location of each ship.

Since you are a new recruit, you are not yet well versed in applying machine learning model to real world problem. So, you plan to consult Dr. Google who is an expert of virtually every field. He informs you that you should use Gaussian mixture model in the above mentioned case. One possible implementation for this model is an EM (expectation-maximization) algorithm. He is also generous enough to give you a pseudocode for this which is given below.

&nbsp;

Let a vector &nbsp;with dimension can be generated from any one of the &nbsp;Gaussian distribution where the probability of selection of Gaussian distribution &nbsp;is &nbsp;where &nbsp;and the probability of generation of &nbsp;from Gaussian distribution &nbsp;is given as,

Got It : (1, m) matrix

To learn a Gaussian mixture model using EM algorithm, we need to maximize the likelihood function with respect to the parameters (comprising the means and covariances of the components and the mixing coefficients). The steps are given below.

<ol>
<li>Initialize the means , covariances and mixing coefficients , and evaluate the initial value of the log likelihood.</li>
<li><strong>E step</strong>: Evaluate the conditional distribution of latent factors using the current parameter values</li>
<li><strong>M step</strong>: Re-estimate the parameters using the conditional distribution of latent factors</li>
</ol>
<strong>weighted mean</strong>

&nbsp;

<ol start="4">
<li>Evaluate the log likelihood and check for convergence of either the parameters or the log likelihood. If the convergence criterion is not satisfied return to step 2.</li>
</ol>
&nbsp;

Now you are excited to get this detailed model and algorithm. However, since this is an issue of national security you want to make sure that the suggestion from Dr. Google is indeed correct. At the outset you want to answer the following questions in your report.

<ol>
<li>Why should you use a Gaussian mixture model (GMM) in the above scenario?</li>
<li>How will you model your data for GMM?</li>
<li>What are the intuitive meaning of the update equations in <strong>M step</strong>?</li>
<li>Derive the log-likelihood function in step 4.</li>
<li>Implement the above pseudocode and estimate the location of enemy ships.</li>
</ol>
&nbsp;

<strong>Special Instructions</strong>

<ol>
<li>This time the report with the answer of first 4 questions is mandatory and will be graded. You have to explain those answers during viva. The report should be in .docx/.pdf and must be available at the time of viva. Write precisely in your own language and keep it as simple as possible. Show detailed derivations for questions 3 and 4.</li>
<li>Although you are allowed to consult Dr. Google, don’t copy anything! If you do copy from internet or from any other person or from any other source, you will be severely punished and it is obvious. More than that, we expect fairness and honesty from you. Don’t disappoint us!</li>
<li>Upload the code and report in Moodle within 12:30 A.M. of 12<sup>th</sup> May, 2018 (Saturday). This is a strict system-imposed deadline for both section A1 and A2.</li>
<li>You are allowed to show the assignment in your own laptop during the final submission. But in that case, ensure an internet connection as you have to instantly download your code from the Moodle and show it.</li>
<li>Contact Sharif sir for any typos or discrepancies in this document.</li>
</ol>

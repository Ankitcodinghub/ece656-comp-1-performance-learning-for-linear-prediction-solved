# ece656-comp-1-performance-learning-for-linear-prediction-solved
**TO GET THIS SOLUTION VISIT:** [ECE656 Comp 1-Performance Learning for Linear Prediction Solved](https://www.ankitcodinghub.com/product/ece656-comp-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98330&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE656 Comp 1-Performance Learning for Linear Prediction Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
The purpose of this computer assignment is to show how performance learning can be used to estimate the unknown parameters of a linear predictor directly from the data. You can MATLAB toolboxes on any other software for this assignment.

<ol>
<li>Download 3-years worth of historical data associated with the daily closing price of a particular stock index (e.g., APPLE) from one of the financial sites e.g., http://finance.yahoo.com/. Use 1/3 of the data for training and the rest for validation and testing.</li>
<li>Consider your data as a time series that could be modeled using a linear autoregressive (AR) model of the form,y(n)=a1y(n−1)+a2y(n−2)+…aN y(n−N)+e(n)
where N is the order of the AR process, e(n) is the driving input which is assumed to be a zero mean white Gaussian random process with variance σ2e , and ai’ s are the model parameters that need to be estimated via the training.
</li>
<li>Choose N=3 i.e. a 3rd order AR model and using an appropriate learning rule covered in class, devise a scheme to estimate the parameters a1, a2 and a3 directly from the data. Present the plot of the learning curve of your algorithm. Check the validity of your results by comparing them with those of the Wiener-Hopf solution using w*= Rxx-1 Rxd. Comment on the convergence behavior and accuracy (i.e. misadjustment vs speed) of the learning.</li>
<li>Study the effects of step size μ on the results. Choose μ= 10-4 and 10-5 and compare the results.</li>
<li>Validate the performance of your stock price predictor, yˆ(n)=a1y(n−1)+a2y(n−2)+…aN y(n−N)on the validation data set by determining the MSE of the estimates i.e</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1N

ε = ∑(y(n) − yˆ(n))2 and distribution of the error. How reliable is your predictor?

</div>
</div>
<div class="layoutArea">
<div class="column">
N n=1

What are the issues with this predictor?

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="6">
<li>Test the behavior of this adaptive predictor on the testing data and comment on the performance.</li>
<li>Provide your results and thorough discussions on your results in a brief report.Note: Please follow the posted guidelines for preparing good reports.</li>
</ol>
</div>
</div>
</div>

**Understanding the logic of** Revenue Margin Analysis with a simple example**




![图片1](./images/image10.png)






Case Study Overview:

We have three products: A, B and C. They are undergoing changes in price, cost and quantity over 2 years; therefore, our revenue margin has changed. Our goal is to answer following questions: (1). What are the **driving factors** in the revenue margin change? (2). What is the **product** mix effect** and how has each product performed with regards to the product mix? (3) Looking at **each product itself**, how has it performed at an operational level?



Here, we provide an analytical framework which consists of two perspectives: top level view which we call **Volume-Mix-Margin Perspective (VMM)** and line level view which we call **Price-Cost-Quantity Perspective (PCQ)**. First, why two instead of one? We **cannot answer all questions** with one view**. When we analyze the mix effect using VMM and focus on the overall product structure, we cannot dive into each product for detailed factor analysis. Vice versa with the PCQ, mix effects will be embedded in each factor and cannot be separately determined. 



Let’s start with the **Volume-Mix-Margin Perspective (VMM**)**.




![图片2](./images/image8.png)






On the global perspective, we can just **consider margin (price **–** cost) and quantity in a two-factor analysis**, how can we break the total revenue margin change of 360 into different drivers? By **controlling variables step by step**. Let's take product A as an example: 

Starting with FY24 Revenue Margin of 100, if we assume **only quantity changes**, while **margin and quantity share remain FY24 level (thus no product structure change)**, how much more revenue margin can we have?



**Volume Effect** = (<span style='color:#0F9ED5'> FY</span><span style='color:#0F9ED5'>25 Total Quantity (F12) </span>x <span style='color:#EC6602'>FY24 A Quantity Share (G2) </span>– <span style='color:#B4A8FF'>FY24 A Quantity (F2</span><span style='color:#B4A8FF'>) </span>) x <span style='color:#00B050'>FY24 A Margin (E2)</span> = ( 80 x 26.7% -20 ) x 5 = 6.6667

**(**E**ffect from volume change excluding the impact of product structure change)**

Now we are 106.6667 for product A revenue margin.



Let's continue with product A at revenue margin of 106.6667. Now we **add one more variable**: **the quantity share of A is changing (as of actual product structure in FY25)**. How much more revenue margin can we have?




![图片3](./images/image4.png)






**Mix Effect** = ( <span style='color:#0F9ED5'>FY</span><span style='color:#0F9ED5'>25 A Quantity (F9) </span>- <span style='color:#EC6602'>FY25 Total Quantity (F12) </span>x <span style='color:#B4A8FF'>FY24 A Quantity Share (G2</span><span style='color:#B4A8FF'>) </span>) x <span style='color:#00B050'>FY24 A Margin (E2) </span>= (25 – 80 x 26.7%) x 5 =18.3333

**(**E**ffect from product structure change)**

Now we are 125 for product A revenue margin.



Final step before reaching FY25 actual revenue margin. Now we **add the last variable, the margin of A is changing**. How much more revenue margin can we have?




![图片4](./images/image1.png)






**Margin Effect** =  <span style='color:#B4A8FF'>FY</span><span style='color:#B4A8FF'>25 A Quantity (F9</span><span style='color:#B4A8FF'>)  </span>x ( <span style='color:#0F9ED5'>FY</span><span style='color:#0F9ED5'>25 A Margin (E9) </span>- <span style='color:#EC6602'>FY24 A Margin (E2</span><span style='color:#EC6602'>) </span>) = 25 x (10 – 5) = 125

**(**E**ffect from product margin change)**

Now we are 250 for product A revenue margin (FY25 actual revenue margin)




![图片5](./images/image13.png)






Revenue margin change is now broken into **volume development, margin change, and structure change.** In total, if there is no structure change, our total quantity from 75 to 80 brought us more revenue margin of 50 **(Volume Effect)**. Compared to this hypothetical case, our structure change brought us 125 more (**Mix Effect**). And lastly, improving margins of A and B brought us 185 more (**Margin Effect**).



However, regarding the structure change, which products are **optimizing our business structure**, which are worth our attention? 



Mix effect just tells us about the **absolute impact from structure change**. We need **a benchmark to determine whether the structure change is favorable or not!**



If we use the **average margin** as a benchmark, we can adjust the mix effect from **absolute impact to relative impact **by adding a mathematical transformation**.**As you can see from the screenshot, the sum of the Structural Optimization Contribution (RM abs) is always same as sum of the mix effect.<span style='color:#E97132'> </span>




![图片6](./images/image12.png)






Take product A as an example:

**Structural Optimization Contribution** (RM abs)** =  ( <span style='color:#0F9ED5'>FY25 A Quantity (F9) </span>- <span style='color:#EC6602'>FY25 Total Quantity (F12)</span><span style='color:#0F9ED5'> x </span><span style='color:#B4A8FF'>FY24 A Quantity Share (G2</span><span style='color:#B4A8FF'>)</span><span style='color:#0F9ED5'> </span>)  x ( <span style='color:#00B050'>FY</span><span style='color:#00B050'>24 A Margin (E2)</span> – <span style='color:#FF66FF'>FY24 AVG Margin (E5</span><span style='color:#FF66FF'>) </span>) = (25 – 80 x 26.7%) x (5 – 10) = -18.3333

**(Contribution to structural optimization in relation to the average** margin**)**



Basic principle here: **the bigger portion of quantity is with our higher-than-average margin **products,** the more favorable is for our business structure!**





What if we use the average revenue margin rate as a benchmark? In addition to replacing the average margin with the average margin rate, we need to **add the **price as a multiplier. **




![图片7](./images/image9.png)






**Structural Optimization Contribution (RM **%**)** =  ( <span style='color:#0F9ED5'>FY25 A Quantity (F9)</span> - <span style='color:#EC6602'>FY25 Total Quantity (F12) </span>x <span style='color:#B4A8FF'>FY24 A Quantity Share (G2</span><span style='color:#B4A8FF'>)</span> )  x ( <span style='color:#00B050'>FY</span><span style='color:#00B050'>24 A Margin</span><span style='color:#00B050'> Rate</span><span style='color:#00B050'> (</span><span style='color:#00B050'>J</span><span style='color:#00B050'>2)</span> – <span style='color:#FF66FF'>FY24 AVG Margin </span><span style='color:#FF66FF'>Rate </span><span style='color:#FF66FF'>(</span><span style='color:#FF66FF'>J</span><span style='color:#FF66FF'>5</span><span style='color:#FF66FF'>) </span>) x <span style='color:#F8BB4E'>FY24 A </span><span style='color:#F8BB4E'>Price</span><span style='color:#F8BB4E'> (C2)</span><span style='color:#FFC000'> </span>= (25 – 80 x 26.7%) x (25% – 29.4%) x 20 = -3.2353

**(Contribution to structural optimization in relation to the average** margin rate**)**



As we can see, two benchmarks give different results. Let’s look at the difference to find out why.


![图片8](./images/image5.png)




**Price Structure Variance** = ( <span style='color:#0F9ED5'>FY</span><span style='color:#0F9ED5'>25 A Quantity (F9)</span> - <span style='color:#EC6602'>FY25 Total Quantity (F12) </span>x <span style='color:#B4A8FF'>FY24 A Quantity Share (G2</span><span style='color:#B4A8FF'>)</span> )  x  <span style='color:#00B050'>FY</span><span style='color:#00B050'>24 A </span><span style='color:#00B050'>AVG </span><span style='color:#00B050'>Margin Rate (J</span><span style='color:#00B050'>5</span><span style='color:#00B050'>)</span> x (<span style='color:#F8BB4E'> </span><span style='color:#FF66FF'>FY</span><span style='color:#FF66FF'>24 A </span><span style='color:#FF66FF'>Price</span><span style='color:#FF66FF'> (</span><span style='color:#FF66FF'>C2</span><span style='color:#FF66FF'>) </span><span style='color:#FF66FF'>- </span><span style='color:#F8BB4E'>FY24 AVG Price (C</span><span style='color:#F8BB4E'>5</span><span style='color:#F8BB4E'>)</span><span style='color:#FF66FF'> </span>) = (25 – 80 x 26.7%) x 29.4% x ( 20 - 34) = -15.0980

From the formula, we can see that the **pricing difference** of our products is the root cause of the difference between two benchmarks’ results.



However, both results are useful for us, since **improving revenue margin rate **and increasing revenue margin are **not **exactly **the **same** goals**. A simple example: product A is priced at 10, with a margin of 9 and a margin rate of 90%; while product B is priced at 1000, with a margin of 100 and a margin rate of 10%. In this case, we have high margin in product B but high margin rate in product A. 



Now, let’s have a look at the complete results of VMM.


![图片9](./images/image2.png)






Still take product A as example, the increased revenue margin is **mainly driven by **margin** improvement**. And from the volume perspective, it is **growing together with the overall **and even proportionally more than the overall**. This is shown in the positive **mix effect** of 18.33. Until now, everything seems fine with product A. However, when we look at both contribution KPIs, product A is showing negative results, meaning **its development is indeed worsening the overall product structure**. Why? Product A is a **low margin product** in relation to the average** (25% against 29.4% on margin rate and 5 against 10 on absolute margin), so **the bigger **product** A's **portion is, the more **unfavorable it** is for our business structure**. Therefore, the conclusion is that **product **A has significantly improved its margin, however **it is still** not good enough**. We should **further work on the margin**, and strategically we should **limit the sales resource allocation **to product** A** until we see that significant margin improvement.



But how to improve further on product A’s margin? For that we need to look at product A separately on an operational level. That’s where the second perspective - **Price-Cost-Quantity Perspective (PCQ)** plays a role. In this analysis, we break the revenue margin change down to the three basic factors – **price, cost and quantity**. How? **Still by controlling variables**. **




![图片10](./images/image14.png)






Product A has a revenue margin change of 150, which is a mixed result from price, cost and quantity changes. 

First, we **keep cost and quantity unchanged and only change the price to FY25 level**.

Price Effect = ( <span style='color:#0F9ED5'>FY</span><span style='color:#0F9ED5'>25 A Price (C9)</span> - <span style='color:#EC6602'>FY24 A Price (C2</span><span style='color:#EC6602'>) </span>) x <span style='color:#B4A8FF'>FY24 A Quantity (F2</span><span style='color:#B4A8FF'>)  </span>= (30 – 20) x 20 =  200

**(**E**ffect from product price change)**




![图片11](./images/image11.png)






Second, we **keep price and quantity unchanged and only change the cost to FY25 level**.

Cost Effect = - ( <span style='color:#0F9ED5'>FY</span><span style='color:#0F9ED5'>25 A Cost (D9) </span>- <span style='color:#EC6602'>FY24 A Cost (D2</span><span style='color:#EC6602'>)</span> ) x <span style='color:#B4A8FF'>FY24 A Quantity (F2</span><span style='color:#B4A8FF'>)  </span>= - (20 – 15) x 20 = -100

**(**E**ffect **from** product cost change)**




![图片12](./images/image7.png)






Third, we **keep price and cost unchanged and only change the quantity to FY25 level**.

Quantity Effect = ( <span style='color:#B4A8FF'>FY</span><span style='color:#B4A8FF'>25 A Quantity (F9)</span> - <span style='color:#00B050'>FY24 A Quantity (F2</span><span style='color:#00B050'>) </span>) x ( <span style='color:#0F9ED5'>FY</span><span style='color:#0F9ED5'>24 A Price (C2)</span> - <span style='color:#EC6602'>FY24 A Cost (D2</span><span style='color:#EC6602'>)</span> )  = (25 – 20) x (20 – 15) = 25

**(**E**ffect from product quantity change)**



Btw, **Quantity Effect is always equal to Volume Effect + Mix Effect** from VMM Perspective.




![图片13](./images/image6.png)






Last, since we are dealing with 3 variables, after we have done the exercises before, mathematically we will still have a remaining item. 



Cross Term= ( <span style='color:#FF66FF'>FY</span><span style='color:#FF66FF'>25 A Quantity (F9) </span>- <span style='color:#F7C600'>FY24 A Quantity (F2</span><span style='color:#F7C600'>) </span>) x ( ( <span style='color:#0F9ED5'>FY25 A Price (C9) </span>- <span style='color:#EC6602'>FY24 A Price (C2</span><span style='color:#EC6602'>) </span>)  - ( <span style='color:#B4A8FF'>FY</span><span style='color:#B4A8FF'>25 A Cost (D9) </span>- <span style='color:#00B050'>FY24 A Cost (D2</span><span style='color:#00B050'>) </span>) ) = (25 – 20) x ( (30 – 20) - (20 – 15) ) = 25

**(**P**art of changed revenue margin from additional quantity with additional price-cost margin)**



Now, let’s look at the complete results of PCQ.




![图片14](./images/image3.png)






As we can see, product A has significantly increased in price and cost at the same time, although margin per unit has improved. Therefore, back to the question from VMM, it’s clear now that product A needs to work on cost reduction to achieve even higher margin.



Now, with the two perspectives combined, we have a holistic view on the performance of product A. Strategically, since product A is currently a low-margin product, until we see significant margin improvement, we should limit the sales resource allocation to product A. Operationally, product A needs to work on cost reduction aiming for higher margin.



This marks the end of the introduction on the revenue margin analysis framework. In this exercise, we answered the questions raised at the beginning: 

(1). What are the driving factors in the revenue margin change? 

(2). What is the product mix effect and how has each product performed with regards to the product mix? 

(3) Looking at each product itself, how has it performed at an operational level? 



I hope you now have a different understanding of how to analyze the product complex with regard to its revenue margin development. And you should definitely try this idea for other similar topics of your real job.








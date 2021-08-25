# Shark Attack Project

<img align="right" src="https://stickershop.line-scdn.net/stickershop/v1/product/1057216/LINEStorePC/main.png" alt="" width="201" height="201" />
 
<h3>Analyze the table and answer the following questions:</h3>

<p>- Which countries are riskier?</br>
- Is it more threatening for men or women?</br>
- Do sharks attack more surfers, swimmers or fishermen?</p></br>


<p><b>Steps:</b></br>
Import the Pandas and Numpy libraries</br>
Read CSV file using <code>encoding = latin-1</code> </br>
Use the <code>info()</code> function to see how much information is null.</br>
I chose the columns to answer the questions: Sex, Activity, Case Number and Country.</br>
Use <code>value_counts()</code> function to get a series containing counts of unique values.</br>
Then, use <code>groupby</code> ,<code>agg</code> ,<code>count</code> and <code>sort</code> methods to group, count and sort the data.</p>

<h3>Conclusion:</h3>

<p>- The country with the highest number of occurrences is the USA, with 2229 cases, followed by Australia with 1338 cases.</br>
- The majority of attacks were on surfers, accounting for 971 - 890 on men. And swimmers there were 869 attacks - 690 in men.</br>
- Worldwide, men have been attacked 5094 times, while women have been attacked 637 times. In the US, men were attacked 1791 times, while women were attacked 337 times.</p>



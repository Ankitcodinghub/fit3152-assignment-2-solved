# fit3152-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [FIT3152 Assignment 2 Solved](https://www.ankitcodinghub.com/product/fit3152-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119564&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FIT3152 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Your task

● The objective of this assignment is to gain familiarity with classification models using R.

Suggested Length ● 4 – 6 A4 pages (for your report) + extra pages as appendix (for your code)

● Font size 11 or 12pt, single spacing

Submission ● PDF file only. Naming convention: FirstnameSecondnameID.pdf ● Via Moodle Assignment Submission.

Late

Penalties ● 10% (2 mark) deduction per calendar day for up to one week.

Instructions and data

The objective of this assignment is to gain familiarity with classification models using R.

You will be using a modified version of the Kaggle competition data: Predict rain tomorrow in Australia. https://www.kaggle.com/jsphyg/weather-dataset-rattle-package The data contains meteorological observations as attributes, and the class attribute “Warmer Tomorrow”.

There are two options for compiling your report:

(1) You can submit a single pdf with R code pasted in as machine-readable text as an appendix, or (2) As an R Markup document that contains the R code with the discussion/text interleaved. Render this as an HTML file and print off as a pdf and submit.

Submit your report as a single PDF with the file name FirstnameSecondnameID.pdf on Moodle.

Creating your data set

Clear your workspace, set the number of significant digits to a sensible value, and use ‘WAUS’ as the default data frame name for the whole data set. Read your data into R and create your individual data using the following code:

rm(list = ls())

WAUS &lt;- read.csv(“WarmerTomorrow2022.csv”) L &lt;- as.data.frame(c(1:49))

set.seed(XXXXXXXX) # Your Student ID is the random seed

L &lt;- L[sample(nrow(L), 10, replace = FALSE),] # sample 10 locations

WAUS &lt;- WAUS[(WAUS$Location %in% L),]

WAUS &lt;- WAUS[sample(nrow(WAUS), 2000, replace = FALSE),] # sample 2000 rows

Questions

1. Explore the data: What is the proportion of days when it is warmer than the previous day

compared to those where it is cooler? Obtain descriptions of the predictor (independent) variables – mean, standard deviations, etc. for real-valued attributes. Is there anything noteworthy in the data? Are there any attributes you need to consider omitting from your analysis? (1 Mark)

2. Document any pre-processing required to make the data set suitable for the model fitting that follows. (1 Mark)

3. Divide your data into a 70% training and 30% test set by adapting the following code (written for the iris data). Use your student ID as the random seed.

set.seed(XXXXXXXX) #Student ID as random seed train.row = sample(1:nrow(iris), 0.7*nrow(iris))

iris.train = iris[train.row,] iris.test = iris[-train.row,]

• Decision Tree

• Naïve Bayes

• Bagging

• Boosting

• Random Forest

5. Using the test data, classify each of the test cases as ‘warmer tomorrow’ or ‘not warmer tomorrow’. Create a confusion matrix and report the accuracy of each model. (1 Mark)

6. Using the test data, calculate the confidence of predicting ‘warmer tomorrow’ for each case and construct an ROC curve for each classifier. You should be able to plot all the curves on the same axis. Use a different colour for each classifier. Calculate the AUC for each classifier. (1 Mark)

7. Create a table comparing the results in parts 5 and 6 for all classifiers. Is there a single “best” classifier? (1 Mark)

12. Write a brief report (suggested length 6 pages) summarizing your results in parts 1 – 11. Use commenting in your R script, where appropriate, to help a reader understand your code. Alternatively combine working, comments and reporting in R Markdown. (1 Mark)

Software

It is expected that you will use R for your data analysis and graphics and tables. You are free to use any R packages you need but please document these in your report and include in your R code.

Description of the data

Attributes 1-3, Day, Month, Year Day, Month, Year of the observation.

Attribute 4, Location The location of the observation.

Attribute 5, MinTemp The daily minimum temperature in degrees Celsius.

Attribute 6, MaxTemp The daily maximum temperature in degrees Celsius.

Attribute 7, Rainfall Rainfall recorded for the day in mm.

Attribute 8, Evaporation The evaporation (mm) in the 24 hours to 9am.

Attribute 9, Sunshine Hours of bright sunshine over the day.

Attribute 10, WindGustDir Direction of strongest wind gust over the day.

Attribute 11, WindGustSpeed Speed (km/h) of the strongest wind gust over the day.

Attribute 12, WindDir9am Direction of the wind at 9am.

Attribute 13, WindDir3pm Direction of the wind at 3pm.

Attribute 14, WindSpeed9am Speed (km/hr) averaged over 10 minutes prior to 9am.

Attribute 15, WindSpeed3pm Speed (km/hr) averaged over 10 minutes prior to 3pm.

Attribute 16, Humidity9am Humidity (percent) at 9am.

Attribute 17, Humidity3pm Humidity (percent) at 3pm.

Attribute 18, Pressure9am Atmospheric pressure (hpa) reduced to mean sea level at 9am.

Attribute 19, Pressure3pm Atmospheric pressure (hpa) reduced to mean sea level at 3pm.

Attribute 20, Cloud9am Fraction of sky obscured by cloud at 9am. This is measured in “oktas”, which are a unit of eigths. It records how many eigths of the sky are obscured by cloud. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast.

Attribute 21, Cloud3pm Fraction of sky obscured by cloud at 3pm.

Attribute 22, Temp9am Temperature (degrees C) at 9am.

Attribute 23, Temp3pm Temperature (degrees C) at 3pm.

Attribute 24, WarmerTomorrow The target variable. Will tomorrow be warmer than today?

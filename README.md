# Project-1---Mental-Health-in-Tech

Data Source:

Our data set are the survey results from OSMH surveys taken between 2017 and 2021
https://osmhhelp.org/research.html

Project Questions:

1. Observing trends by demographics
A) What correlations can be found between demographics (gender, age) and awareness of mental healthcare benefits?
B) What correlations can be found between country and mental health benefits provided by employer?

2. Observing trends by industry
A) Are tech employees more likely than non-tech employees to have a mental health condition?
B) Are tech companies more likely than non-tech companies to offer mental health benefits?

3. Observing trends before and after pandemic
A) How much importance did employers place on mental health before and after the pandemic?
B) How comfortable did employees feel discussing mental health with their direct supervisor(s) before and after the pandemic?

Totals were obtained for each response by year and plotted onto bar charts.

For question 3a, since the responses were numerical, the mean responses were calculated and an individual t-test was performed. A statistical analysis could not be performed for question 3b since the responses were non-numerical.

Resources:
Stack Overflow

4. Observing trends among employees with/without existing mental health disorders
A) Participants with/without mental health disorders vs protected anonymity
B) Participants with/without mental health disorders vs ability to take mental health leave

For observing trends in tech workers with/without mental disorders, I reduced the data down to rows only involving tech workers and then found the count of participants with/without mental health disorders as well as counts for participants responses for ease of asking for leave and ability to remain anonymous when using menatl health related benefits. 

I then plotted the results on bar charts and ran poisson means tests on the results to determine their significance. 

The difference in ratio was statistically significant between participants without diagnosed mental health disorders who found it very easy to ask for leave vs. both difficult and somewhat easy with P values of 0.008 and 0.00005 respectively. 

The difference in ratio was not statistically significant between participants without diagnosed mental health disorders who can remain anonymous vs. can't remain anonymous with a P value of 0.69.

Sources:
code for calculating percentage of group
https://stackoverflow.com/questions/75090908/pandas-matplotlib-bar-plot-with-multi-index-dataframe

multiindex bar chart formatting:
https://stackoverflow.com/questions/34248741/plotting-pandas-multiindex-bar-chart

code for cropping chart correctly
https://stackoverflow.com/questions/37427362/plt-show-shows-full-graph-but-savefig-is-cropping-the-image/37428142


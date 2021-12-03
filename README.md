# 2021Fall_finals: Job Creation in The U.S.

# Group Member: Yiwen Xu (GitHub ID: softkittywarmkitty), Qinwen Yang (GitHub ID: zao-YQW)

# Background

Economic recession will affect every aspect of life. For job seekers and employees, the direct impact of the recession is the reduction of job positions, or even worse, layoffs from the company. 

We found an article published in 2012, which divided the companies into three categories and mainly studied the changing trend of job positions of private companies in the market and the resilience speed of those companies after the economy has passed. 

Since this article was published in 2012, Covid-19 did not appear. The impact of the Covid-19 on the economy in recent years is not negligible. We want to add the Covid-19 daily infection case trend in the US dataset and daily vaccinated number (or rate) dataset from the CDC website to see how the law of change follows. 

**-Article Source:** 

Tasci, M., & Burgen, E. (2012, February 6). Job creation by small and large firms over the business cycle. website. Retrieved December 2, 2021, from https://www.clevelandfed.org/en/newsroom-and-events/publications/economic-trends/2012-economic-trends/et-20120206-job-creation-by-small-and-large-firms-over-the-business-cycle.aspx. 

**-Dataset Involved:** 

Business Employment Dynamics(BDE) dataset : https://www.bls.gov/bdm/bdmfirmsize.htm#SIZE1
COVID-19 daily cases trend in the U.S. dataset: https://covid.cdc.gov/covid-data-tracker/#trends_dailycases
COVID-19 daily vaccinations trend in the U.S. dataset: https://covid.cdc.gov/covid-data-tracker/#vaccination-trends_vacctrends-total-change

# Analysis of Results
The analysis results in the article are generally correct. After we add data from recent years, we find that Covid-19 has a greater impact on the job market than The Great Recession.

The first visualization is the seasonally adjusted change of payroll employment. We can see in the figure that both the 2001 and 2008's recessions do have a certain impact on payroll employment, but the recovery period after the recession did not change significantly. During the pandemic, the descending level of payroll employment reaches an exaggerated level, around -15000(thousands). When the epidemic was relatively stable and the economy began to recover, the growth of payroll employment was also unprecedentedly high, nearly 4,000 (thousands).
![image](https://user-images.githubusercontent.com/73344778/144548677-170af830-5a14-46a1-bf3f-428c92eda4a6.png)

The same situation occurs in the following visualizations.
![image](https://user-images.githubusercontent.com/73344778/144548712-bb253991-949f-4204-a12c-ef85332857ee.png)

![image](https://user-images.githubusercontent.com/73344778/144548723-84c3df12-b757-44e1-ab07-08b8ad0302c6.png)

![image](https://user-images.githubusercontent.com/73344778/144548739-2dc49659-ae5b-40f2-a669-0861a1033094.png)

![image](https://user-images.githubusercontent.com/73344778/144548746-63aaf1f1-4f56-40d0-b337-33535c22d38d.png)

But when redrawing the last visualization in the article, we didn't get the same result. Although the trend of each line is roughly the same, the data is unmatched. We are not sure if it is because the author accidentally misrepresented the company classification--because in the previous classification, the large firms were usually the companies with more than 500 employees, but in this one, it was changed to 250 employees--or the author's data is different from ours.
![image](https://user-images.githubusercontent.com/73344778/144548789-3122794a-fedc-4c69-894b-6fe7a2f1dedb.png)


# Hypotheses:
**1. The number of Covid-19 cases in the United States was negatively correlated with employment opportunities at the beginning, but over time, the increase in cases will not affect employment opportunities.**
![image](https://user-images.githubusercontent.com/73344778/144548837-158a28e7-a027-47cd-a434-0f0a349a4aff.png)
![image](https://user-images.githubusercontent.com/73344778/144548849-da98c328-692d-48e5-aefa-62169be50cdf.png)
As we can see in the above visualization, at the beginning of 2020, job gains and the increases in the number of Covid cases show a significant negative correlation. In the third quarter, job gains seem no longer to be affected by the increase of Covid cases. We think this may be because a large number of employees were fired or resigned at the beginning of the epidemic, and a few months later, due to financial pressure or other reasons, they had to find a job. At the same time, the national economy needs to recover. Therefore, various industries have resumed many positions after the epidemic was relatively stable.

**2. In general, big companies have better resilience capabilities after the epidemic pass.**
![image](https://user-images.githubusercontent.com/73344778/144548889-6edf3979-3dab-487d-a6df-9b3d5614e9df.png)
![image](https://user-images.githubusercontent.com/73344778/144548897-9f773807-11c1-4ecc-b367-28acfa5e1d2d.png)
In the figure, we can find that when the number of cases of the epidemic increases, those small companies are most affected, while job changes in medium and large companies tend to be stable. This is not the same as previous recessions. Although the recovery speed of small companies in the figure does not seem to be slow, this is because of the large number of small companies. Therefore, large and medium-sized companies will have a better ability to resist risks and recover relatively quickly.

**3. The increase in the coverage of the Covid-19 vaccination does not bring more job opportunities.**
![image](https://user-images.githubusercontent.com/73344778/144548930-be2c96cd-9597-47ab-a2a7-13e9f21be6cd.png)
![image](https://user-images.githubusercontent.com/73344778/144548938-5f2e0056-4b10-4f46-8362-484b864dbc35.png)
Although we hope to see the increase in vaccine injections can bring more job opportunities, this result did not appear. We guess that there may be the following reasons: 1) the epidemic has lasted for nearly a year before the vaccine injection, the impact of the epidemic has been greatly reduced, and the vaccine injection has only made the current situation more stable, rather than similar to a "booster." 2) The overlap time of the datasets is too short. The labor bureau’s employment data only counts up to March this year, and the vaccine injection starts at the end of last year. The overlap between the two is only three months. It may cause the impact of the vaccine injection not be reflected on the employment situation so quickly.


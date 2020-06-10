# COVID-19 VIETNAM DATASET - AN OVERVIEW PICTURE OF THE PANDEMIC AT COUNTRY LEVEL
## by Tran Nguyen

*This work was created to support the data exploratory and analysis of the '[vietnam-covid19-patient-dataset'](https://www.kaggle.com/nhntran/vietnam-covid19-patient-dataset) published on Kaggle.*

*The writen up report for this analysis could be found [here](https://towardsdatascience.com/covid-19-what-do-we-know-about-the-situation-in-vietnam-82c195163d7e).*

*A nice visualization of all Vietnam COVID-19 patients could be found [here](https://medium.com/@tranhnnguyenvn/a-full-picture-of-vietnam-covid-19-patients-496f7ccad3ea).*

*This work on the specific country data in Vietnam can also be found at [kaggle](https://www.kaggle.com/nhntran/covid-19-vietnam-data-eda-and-visualization?scriptVersionId=32963257) together with [another kernel](https://www.kaggle.com/nhntran/covid-19-the-world-data-eda-and-visualization/edit/run/32144597) which is targeted on global COVID data.*

## **INTRODUCTION**

**CONTEXT:**

On December 31, 2019, Chinese officials informed the first case of COVID-19 in Wuhan (China). Around the end of January, 2020, many countries (the US, the UK, South Korea, etc.), including Vietnam, reported their first COVID-19 cases.

While the number of confirmed cases and deaths has exponentially risen in other countries, **Vietnam currently only has 270 COVID-19 cases in TOTAL and NO FATALITIES**.

One remarkable thing in Vietnam is the fact that privacy laws are not as stringent as in the US, Canada or the EU. Therefore, **COVID-19 patient data in Vietnam is publicly available**. (To be more transparent and effective in COVID-19 contact tracing task, Vietnam COVID-19 patient data is publicly available on the Vietnam Ministry of Health's website and on the news.) 

The tradeoff in personal privacy, in this circumtance, provides the data science community the opportunity to look into more details about the COVID-19 pandemic in many aspects, and at the country level.

I hope this analysis will give you some inspirations on the topic.


**DATA COLLECTION:**

Data was acquired by web scrapping with manually curated from the Vietnam Ministry of Health's website (https://ncov.moh.gov.vn/) and other mainstream media in Vietnam (cited specifically in each data row).


**DISCLAIMER:**

* This is my personal work with no link to any organization. Although this analysis is data-driven and hence provides some insights about the government strategy as well as patient characteristics in Vietnam, my comments reflect my personal perspectives.
* My results are based on the data collected from the Vietnam Health Ministry website and the mainstream media in Vietnam. Therefore, the data is likely to be biased and reflects what is publicly available on the internet. However, it can served as a good reference for someone who are curious about the COVID-19 pandemic in Vietnam.

# Pharmaceutical data anaylsis

- - -

## **Objective:**
The objective of this project is to analyze data on mice treated with a variety of drug regimes to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare in treating squamous cell carcinoma, a commonly occurring form of skin cancer. 

Using Matplotlib, the following graphs were created:
* Scatter plot: Treatment duration (days) vs. tumor volume.
* Scatter plot: Treatment duration (days) vs. number of metastatic (cancer spreading) sites.
* Scatter plot: Treatment duration (days) vs. survival rate (%).
* Bar graph: Treatment vs. total % tumor volume change.

## **Tools:**
Python -  Matplotlib, Pandas, Numpy, Seaborn

## **Screenshots (Graphs):**
![graph1.png](analysis/Fig1.PNG)
![graph2.png](analysis/Fig2.PNG)
![graph3.png](analysis/Fig3.PNG)
![graph4.png](analysis/Fig4.PNG)

### Analysis

* Overall, it is clear that Capomulin outperforms all other treatment options in the screen.
* Capomulin was the only treatment to reduce tumor volume. It held to a 19% reduction in tumor volume over the course of trial, whereas all other drugs were correlated with an increase in tumor volume by roughly 40-50%.
* Capomulin greatly limited the spread of the tumor compared to other treatment options. By study end, the average mouse on Capomulin had only 1 new metastatic site, as opposed to the average 2-3 found in mice of other treatment options.
* Lastly, mice on the Capomulin treatment had the highest survival rate of any treatment in the screen. Over 90% of mice treated by Capomulin survived the full duration of the trial, compared to only 35-45% of mice on other treatment options.



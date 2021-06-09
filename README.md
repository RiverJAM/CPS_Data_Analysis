# CPS Data Analysis Project

>Analyzing Charter School performance

---

#### Central Research Questions
1. Does student performance at Charter Schools differ from Neighborhood Public Schools?
2. Is there a difference in teacher retention at Charter schools compared to Neighborhood Public schools?
3. Does teacher salary correlate with Student Growth or Achievement?
4. Do Charter and Neighborhood schools differ in teacher retention?

---

#### Technologies Used
1. Excel
2. Python (SciPy, Pandas, Jupyter Notebook)
3. Matplotlib and Plotly

### Data Sources
https://www.cps.edu/about/district-data/

## Findings

### Charter v Neighborhood Public

Do Charter Schools perform differently than Neighborhood Public schools on average? Our outcome metrics to gauge school performance were graduation rates, test scores, and college admissions.

##### Do Charter Schools differ from Neighborhood Public Schools in their Graduation rates?

H<sub>O</sub>: µ<sub>1</sub> - µ<sub>2</sub> = 0 (There is no difference in the mean graduation rates between Charter and Neighborhood Public schools)

H<sub>A</sub>: µ<sub>1</sub> - µ<sub>2</sub> ≠ 0 (There is a difference in the mean graduation rates between Charter and Neighborhood Public schools)

We reject the null hypothesis (for alpha =.05). All p-values were below .01. The details of the Anova are in "Playing with Pies-Copy1.ipynb"

The data show that charter schools have higher 4 and 5 year graduation rates. Additionally, Neighborhood schools have a greater range of graduation rates.

![alt text](https://github.com/RiverJAM/CPS_Data_Analysis/blob/main/output_data/Grad41vST_2018.png "figure 1")
![alt text](https://github.com/RiverJAM/CPS_Data_Analysis/blob/main/output_data/Grad41vST_2019.png "figure 2")

![alt text](https://github.com/RiverJAM/CPS_Data_Analysis/blob/main/output_data/2018Grad5vST.png "figure 3")
![alt text](https://github.com/RiverJAM/CPS_Data_Analysis/blob/main/output_data/2019Grad5vST.png "figure 4")
---

## Teacher Retention

H<sub>O</sub>: µ<sub>1</sub> - µ<sub>2</sub> = 0 (There is no difference in the mean retention rates between Charter and Neighborhood Public schools)

H<sub>A</sub>: µ<sub>1</sub> - µ<sub>2</sub> ≠ 0 (There is a difference in the mean retention rates between Charter and Neighborhood Public schools)

For this analysis, we used 95% confidence intervals. µ<sub>1</sub> is 0.844871794871795 and µ<sub>2</sub> is 0.4530434782608695 (Neighborhood and Charter respectively). The confidence interval for difference in Teacher Retention is from 0.615983390189514 and 0.16767324303233697. We reject the null. The data show a significantly higher teacher retention in Neighborhood schools.

---
## Does Salary correlate with Student Acheivement?

![alt text](https://github.com/RiverJAM/CPS_Data_Analysis/blob/main/output_data/CollegeEnvSalary.png)


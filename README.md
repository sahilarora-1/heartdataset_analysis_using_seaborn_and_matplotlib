# Heart Disease Dataset Analysis

This repository contains exploratory data analysis (EDA) and visualizations on the Cleveland Heart Disease dataset. The goal is to uncover meaningful patterns about heart disease risk factors using Python, Matplotlib, and Seaborn.

📂 Project Structure heart_cleveland_upload- the dataset used HeartDisease.ipynb -Notebook with charts and code README.md - Project documentation

# 📊 Visualizations Included

The notebook demonstrates different types of plots to analyze medical attributes:
# MATPLOTLIB CHARTS

SCATTER PLOT using matplotlib library( Distrubution of Age)
![chart1](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/distribution_of_age_1.png)
this charts shows distribution of age with number of people; as per chart this dataset maximum people are betwwen age 55 to 60.
maximum number of people are in 58 age with a number of 18
BAR CHART( types of chest pain)
![chart 2 shows type of pain](https://github.com/sahilarora1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/typesofchestpain_1.png)
the second chart is a bar chart showing different types of chest pains like Typical angina, Atypical Angina, Non-anginal Pain,Asymptomatic.
More than 140 people face Asymptomatic chest pain represented by blue color.(maximum people suffer through this pain)
More than 80 people suffer  Non-anginal Pain represented by purple color.
More than 50 people suffer Atypical angina pain represented by pink color.
More than 20 suffer Typical angina pain represented by by red color.(minimum people suffer this pain)

BAR CHART (showing sugar level of people)
![sugar level](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/barchart_showing_sugarlevel3.png)
Most of the people around 250 (represented by red color) have high sugar level which effects their body and there are only 45(represented by blue chart) people those have normal sugar level so this shows people with high sugar levels are more prone to heart attack.

HISTOGRAM ( showing heartbeats of people )
![Heartbeat data](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/histchartshowing_heartbeatrate.png)
This histogram shows heartbeats of people. intervals on X-axis shows the range or vaue of heartbeat maximum number of people have high heartbeat around 150-180 which shows high chances of heart attack.

PIE CHART(showing number of vessels visble in test)
![number of vessels visible](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/numberofvessselsvisible_5.png)
this pie charts showing how many vessels are visible in the test.
-Maximum number of people's no vessels were visible around 58.6 % . more prone to heartattack
-only 6.7% people's three vessels were visible. have good heart
-12.8 % of people's only two vessels were visible
-around 21.9% people have one vessel visible(also have high chances of heart attack or other heart related diseases)

# SEABORN CHARTS

BOX PLOT SWARM OVERLAY(showing the age distribution by sex and heart condition)

![boxplot](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/agedistributionbysex_6.png)
-The x-axis represents sex (Male vs. Female), while the y-axis represents age.
-The two colors indicate different groups: red (heart condition present) and blue (no heart condition).
-The box shows the interquartile range (middle 50% of ages), with the line inside marking the median age.
-The whiskers extend to show variability, while dots outside are outliers.
-From the plot, females with heart conditions tend to be slightly older on average compared to males, and overall age variation is higher among males.

COUNT PLOT( thallium stress vs condition between MALE and FEMALE)
![countplot](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/thalliumstress_vs_condition_7.png)
This bar chart shows the distribution of Thallium stress test results (thal) across males and females. Most patients fall under the Normal category, with nearly equal counts for males and females. However, a much larger proportion of males show a “Reversible defect”, while very few females fall into this group. The Fixed defect category is relatively rare in both sexes. This indicates that abnormal thallium test results (especially reversible defects) are more common in men compared to women.

RESTING BP VS Cholestrol
![Resting Blood Pressure vs Cholesterol](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/BP_vs_cholestrol.png)

This scatter plot shows the relationship between resting blood pressure (trestbps) and cholesterol (chol). Each point represents a patient, and the red line indicates the regression trend. The plot suggests a slight positive correlation: as resting blood pressure increases, cholesterol levels also tend to increase, though the relationship is weak and scattered. This indicates that while higher blood pressure may be associated with higher cholesterol, other factors are also influencing cholesterol levels.

LINE PLOT(Maximum Heart Rate by Age)
![Maximum Heart Rate by Age](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/Heart_ratebyage_9.png)
This line plot shows the trend of maximum heart rate achieved (thalach) across different ages, separated by heart condition (0 = no disease, 1 = disease). Overall, maximum heart rate tends to decrease with age for both groups. Patients without heart disease (blue line) generally achieve higher heart rates compared to those with heart disease (orange line). The shaded regions represent variability, showing more fluctuations in older age groups.

KDE PLOT(Age Distribution by Heart Disease Condition)
![KDE PLOT](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/age_by_disease_10.png)

This KDE plot compares the age distribution of patients with and without heart disease.
Condition 0 = No heart disease
Condition 1 = Presence of heart disease
The plot shows that patients with heart disease (orange curve) are generally older, with most cases concentrated around ages 55–65. Meanwhile, patients without heart disease (green curve) tend to be younger, with a broader distribution across ages 40–55.


HIST PLOT(Age Distribution Chart)
![HISTPLOT](https://github.com/sahilarora-1/heartdataset_analysis_using_seaborn_and_matplotlib/blob/main/images/agedistribution_using_hist_11.png)
The above histogram shows the distribution of ages within the dataset.
The x-axis (Age) represents the age of individuals.
The y-axis (Count) represents the number of individuals in each age group.
The bars (in red) show the frequency of ages grouped into bins.
The red curve is a Kernel Density Estimate (KDE), which provides a smooth approximation of the distribution, making it easier to visualize overall patterns.
From the chart, we can observe:
Most individuals fall between the ages of 40 and 70.
The peak frequency is around the 55–60 age range, meaning this is the most common age group.
The distribution is roughly bell-shaped, though slightly skewed.

# 🛠️ Tech Stack

Python 3.x

Pandas

Numpy

Matplotlib

Seaborn

Jupyter Lab

# 🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/heart-disease-analysis.git cd heart-disease-analysis

Install dependencies:

pip install -r requirements.txt

Open the notebook in Jupyter:

jupyter lab

Run all cells to reproduce the analysis.

# 📌 Dataset

The dataset used is the Cleveland Heart Disease dataset, available from the UCI Machine Learning Repository.

# ✨ Future Improvements

Add correlation heatmaps for all features

Perform feature engineering for predictive modeling

Build machine learning models to classify heart disease risk

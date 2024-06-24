# Drug Consumption Classification

### Project Overview

This project involves analyzing and classifying drug consumption patterns based on demographic, psychological, and behavioral data. The dataset includes features such as age, gender, education, country, ethnicity, personality scores (Nscore, Escore, Oscore, Ascore, Cscore),psychological traits like Impulsiveness and Sensation Seeking (SS) and information on the use of various drugs over different time periods. The goal is to uncover patterns and predictors in drug use behavior, which can provide valuable insights for public health interventions and policy-making.

### The Problem Area

Drug abuse remains a significant public health crisis, affecting millions of individuals and communities worldwide. It leads to severe health complications, social problems, economic burdens, and legal issues. The complexity of drug abuse necessitates a multi-faceted approach to understanding, predicting, and mitigating its impact. The primary problem area addressed by this project is the need for accurate classification and prediction of drug consumption patterns to better inform prevention and intervention strategies.

**Challenges and opportunities to address:**

**Challenges:**

1.**Data Quality and Availability:**
**Challenge:** Obtaining comprehensive and high-quality data on drug use is difficult. There may be issues with missing data, inaccuracies, and inconsistencies due to self-reporting biases and underreporting.
**Opportunity:** Collaborate with healthcare providers, rehabilitation centers, and government agencies to access and integrate diverse datasets. Use advanced data cleaning and imputation techniques to handle missing or incomplete data.

2.**Privacy and Ethical Concerns:**
**Challenge:** Handling sensitive data on drug use raises significant privacy and ethical issues. Ensuring the confidentiality and security of individuals' data is paramount.
**Opportunity:** Implement robust data protection measures and ethical guidelines. Use de-identified data and secure data-sharing agreements to maintain privacy while enabling research.

3.**Complexity of Drug Use Behavior:**
**Challenge:** Drug use behavior is influenced by a multitude of factors, including psychological, social, economic, and environmental aspects. Modeling such complex behavior accurately is challenging.
**Opportunity:** Employ advanced machine learning and AI techniques that can handle complex, multi-dimensional data. Use techniques like ensemble learning, deep learning, and feature engineering to capture the intricate relationships between variables.

4.**Intervention Effectiveness:**
**Challenge:** Developing interventions that are both effective and scalable can be difficult. Interventions need to be tailored to diverse populations and settings, which requires a deep understanding of the target groups.
**Opportunity:** Use data-driven insights to design personalized and targeted interventions. Implement pilot programs to test and refine these interventions before scaling up. Leverage technology for scalable solutions, such as mobile health applications and online support systems.

5.**Policy and Regulatory Barriers:**
**Challenge:** Navigating the regulatory landscape and ensuring compliance with laws and policies related to drug use and data usage can be restrictive and complex.
**Opportunity:** Engage with policymakers and regulatory bodies to advocate for data-driven approaches to drug prevention and treatment. Use research findings to inform policy changes that support effective interventions and data sharing for public health purposes.

**Opportunities:**

1.**Predictive Analytics for Early Intervention:**

**Opportunity:** Use predictive modeling to identify individuals at high risk of drug abuse early on. This can enable timely interventions that prevent the escalation of substance use and related harms.
**Application:** Develop risk assessment tools that healthcare providers can use to screen patients and offer targeted support and resources.

2.**Personalized Treatment Plans:**
**Opportunity:** Leverage data to create personalized treatment plans based on an individual's specific risk factors, psychological profile, and drug use history.
**Application:** Implement personalized treatment strategies in rehabilitation centers, enhancing the effectiveness of programs and improving patient outcomes.

3.**Enhanced Public Health Surveillance:**
**Opportunity:** Improve public health surveillance systems by integrating data from various sources, enabling real-time monitoring of drug use trends and emerging threats.
**Application:** Use this data to inform public health campaigns, allocate resources more effectively, and respond rapidly to outbreaks of substance abuse.

4.**Community-Based Programs:**
**Opportunity:** Design community-based programs that are informed by local data, addressing the specific needs and challenges of different communities.
**Application:** Work with community organizations to implement evidence-based prevention and support programs, increasing their relevance and impact.

5.**Educational and Awareness Campaigns:**
**Opportunity:** Use insights from data analysis to develop targeted educational and awareness campaigns that address misconceptions and provide accurate information about drug use and its risks.
**Application:** Create tailored messages for different demographic groups, utilizing social media, schools, workplaces, and other platforms to reach a wide audience.

By addressing these challenges and leveraging the opportunities, the project can make significant strides in understanding and mitigating drug abuse, ultimately leading to better health outcomes and more effective public health strategies.



### The User

The Drug Consumption Classification project has the potential to significantly impact various stakeholders by providing valuable insights and tools to combat drug abuse. Through predictive modeling, targeted interventions, and data-driven decision-making, the project aims to improve public health outcomes and enhance the effectiveness of prevention and treatment programs.

**Primary Users:**
1) Public Health Officials and Policymakers
2) Healthcare Providers and Practitioners
3) Rehabilitation Centers and Counselors
4) Researchers and Academics
5) Non-Governmental Organizations (NGOs) and Community Groups

**Secondary Beneficiaries:**
1) Individuals and Families
2) Society at Large
3) Employers and Workplaces

### The Big Idea
Machine learning offers robust methodologies to address the identified challenges:

The Drug Consumption Classification project leverages data science to tackle the pervasive issue of drug abuse by identifying patterns and predictors of drug use based on demographic, psychological, and behavioral data. By developing predictive models and data-driven insights, the project aims to enable early identification of at-risk individuals, personalize intervention and treatment plans, and optimize resource allocation for public health strategies. This innovative approach not only benefits public health officials, healthcare providers, rehabilitation centers, researchers, and community organizations but also positively impacts individuals, families, society at large, and workplaces. Ultimately, the project seeks to reduce drug abuse rates, improve public health outcomes, and enhance the effectiveness of prevention and treatment programs.

### The Impact
The societal and business implications are significant:

1.**Improved Public Health:**

**Impact:** Early identification and intervention can prevent drug abuse escalation, reducing healthcare burdens and drug-related deaths.
**Fact:** Nearly 92,000 drug overdose deaths occurred in the U.S. in 2020.

2.**Enhanced Quality of Life:**
**Impact:** Personalized treatment improves recovery rates, benefiting individuals and families, and fostering healthier communities.
**Fact:** Effective interventions can significantly lower the $740 billion annual cost of drug-related healthcare, lost productivity, and criminal justice expenses in the U.S.

3.**Workplace Safety and Productivity:**
**Impact:** Addressing drug abuse reduces absenteeism, improves presenteeism, and lowers health insurance costs, boosting overall productivity.
**Fact:** Businesses can save on healthcare costs and enhance workforce efficiency by supporting drug abuse interventions.

4.**Corporate Social Responsibility and Innovation:**
**Impact:** Companies can enhance their reputation and community ties by engaging in public health initiatives, and capitalize on market opportunities in health technologies.
**Fact:** Collaborations with healthcare prov
iders for developing intervention strategies can position businesses as leaders in corporate social responsibility.

## Dataset Overview

Database contains records for 1885 respondents. For each respondent 12 attributes are known: Personality measurements which include NEO-FFI-R (neuroticism, extraversion, openness to experience, agreeableness, and conscientiousness), BIS-11 (impulsivity), and ImpSS (sensation seeking), level of education, age, gender, country of residence and ethnicity. All input attributes are originally categorical and are quantified. After quantification values of all input features can be considered as real-valued. In addition, participants were questioned concerning their use of 18 legal and illegal drugs (alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, mushrooms, nicotine and volatile substance abuse and one fictitious drug (Semeron) which was introduced to identify over-claimers. For each drug they have to select one of the answers: never used the drug, used it over a decade ago, or in the last decade, year, month, week, or day. Database contains 18 classification problems. Each of independent label variables contains seven classes: "Never Used", "Used over a Decade Ago", "Used in Last Decade", "Used in Last Year", "Used in Last Month", "Used in Last Week", and "Used in Last Day".



## Project Organization

| File | Description |
| ------ | ----------- |
| README.md | The main README document for developers using this project |
| 'Need to fill in' | Initial presentation of the project including EDA |
| data | Drugs Consumption Classification Dataset (https://www.kaggle.com/datasets/mexwell/drug-consumption-classification). |
| notebooks | Project Notebook |
| app | ML model |



## Table of contents

- Durg Consumption Classification Dataset 
- Data Download, Cleaning & EDA
- Modelling
- Conclusions
- Citation

### Durg Consumption Classification Dataset  (Data Dictionary)

#### `drug_consumption.csv` - numeric and categorical data
| Column | Description |
| ------ | ----------- |
| ID | Unique ID for individual user |
| Age | Describes the age range of the individuals |
| Gender | Indicates the gender of the individual |
| Education | Represents the highest level of education attained by the individual |
| Country | Indicates the country of residence of the individual |
| Ethnicity | Describes the ethnic background of the individual |
| Nscore | Nscore (Neuroticism Score): Quantifies the tendency towards emotional instability and anxiety |
| Escore | Escore (Extraversion Score): Measures the tendency to be outgoing, sociable, and energetic |
| Oscore | Oscore (Openness Score): Indicates the level of creativity and openness to new experiences |
| Ascore | Ascore (Agreeableness Score): Represents the tendency to be compassionate and cooperative |
| Cscore | Cscore (Conscientiousness Score): Measures the level of self-discipline and goal-directed behavior |
| Impulsive | Quantifies the level of impulsiveness of the individual
| SS | SS (Sensation Seeking): Represents the tendency to seek novel and thrilling experiences |
| Alcohol | Indicates the frequency of alcohol consumption |
| Amphet | Amphet (Amphetamines): Indicates the frequency of amphetamine use |
| Amyl | Amyl (Amyl Nitrite): Indicates the frequency of amyl nitrite use |
| Benzos | Benzos (Benzodiazepines): Indicates the frequency of benzodiazepine use |
| Caff | Caff (Caffeine): Indicates the frequency of caffeine consumption |
| Cannabis | Indicates the frequency of cannabis use |
| Choc | Choc (Chocolate): Indicates the frequency of chocolate consumption |
| Coke | Coke (Cocaine): Indicates the frequency of cocaine use |
| Crack | Crack (Crack Cocaine): Indicates the frequency of crack cocaine use |
| Ecstasy | Indicates the frequency of ecstasy use |
| Heroin | Indicates the frequency of heroin use |
| Ketamine | Indicates the frequency of ketamine use |
| Legalh | Legalh (Legal Highs): Indicates the frequency of legal highs use |
| LSD | Indicates the frequency of LSD use |
| Meth | Meth (Methadone): Indicates the frequency of methadone use |
| Mushrooms | Indicates the frequency of hallucinogenic mushrooms use |
| Nicotine | Indicates the frequency of nicotine use |
| Semer | Semer (Semeron): Indicates the frequency of semeron use |
| VSA | VSA (Volatile Substance Abuse): Indicates the frequency of volatile substance abuse |


This file is typically used for training machine learning models. Each of these attributes provides valuable information about the demographic, psychological, and substance use characteristics of individuals, allowing for a comprehensive analysis of drug consumption patterns.



## Data Download, Cleaning & Exploratory Data Analysis

In our Drug Consumption Classification Analysis project, we tackle Exploratory Data Analysis (EDA) in three main phases. First, we download the dataset from Kaggle and preprocess it, mapping the original coded values to human-readable categories to enhance interpretability. This mapping process applies to all attributes except for the ID, which serves as a unique identifier. With the dataset prepared, we delve into exploring the distribution and characteristics of the data. Each attribute, originally represented by coded range numbers and classes, is transformed into meaningful categories for analysis. Leveraging the transformed data, we generate insights and identify patterns. This allows us to uncover valuable information about drug consumption behavior and associated factors, guiding further analysis and decision-making processes. 

One of the example for `Gender` as below

| Column | Original Values | Mapped Values
| ------ | ----------- | --------------- |
| Gender | 0.48246 | Female |
| Gender | -0.48246 | Male |


Secondly, we check the dataset for any duplicates, missing entries, and errors to make sure the data is accurate.

Next, we move into a detailed examination of the data, using graphs and charts to spot trends and investigate how different factors, like age, gender, education, personality scores and different drugs related.

Key takeaways from our EDA Part 1 include:
Age shows significant negative correlations with many substance uses, suggesting younger individuals are more likely to engage in these activities.
Gender influences substance use patterns, with males possibly more inclined towards certain substances.
Personality traits like Neuroticism, Extraversion, and Sensation Seeking are strongly related to substance use behaviors.
Country and Education also play a role in substance use tendencies, indicating potential cultural and socio-economic influences.

Key takeaways from our EDA Part 2 include:
Inter-trait Dynamics: High Neuroticism is linked with lower scores in Openness, Agreeableness, Conscientiousness, and Extraversion. Conversely, high Extraversion is associated with lower scores in Openness, Agreeableness, and Conscientiousness.

Positive Correlations: Openness correlates positively with both Conscientiousness and Agreeableness, while Agreeableness and Conscientiousness are also positively correlated, suggesting individuals high in one of these traits tend to score high in the others.

Educational Attainment: Individuals with a Professional Certificate/Diploma exhibit higher drug consumption rates across various drug types compared to other educational groups.
Age Group: Young adults aged 18-24, followed by those aged 25-34, show higher drug usage rates, indicating a significant correlation between younger age and increased drug consumption.



## Preprocessing:
I will continue doing preproecssing and creating heat map and analysis correlation and coefficeint between all the features in the second part of EDA.

Handling Missing Data:
Null or NA records have been systematically removed to ensure data integrity and reliability for analysis.

Categorical Feature Transformation:
Categorical features have been methodically converted into dummy variables, facilitating clearer interpretation and integration into analytical models.

## Modeling
Base Model:
logistic regression, decision trees.
The provided results compare the performance of Logistic Regression and Decision Tree models in predicting heroin usage.

Logistic Regression: For non-drug users (class 0), precision is 99%, recall is 98%, and F1-score is 98%. This indicates very few false positives and high accuracy in identifying non-users. For drug users (class 1), precision is 27%, recall is 50%, and F1-score is 35%. This shows a higher rate of false positives and a moderate ability to identify actual drug users. Overall accuracy is 97%.

Decision Tree: For non-drug users (class 0), precision is 99%, recall is 98%, and F1-score is 98%. This mirrors the Logistic Regression model's performance in identifying non-users. For drug users (class 1), precision is 43%, recall is 38%, and F1-score is 40%. This indicates an improvement over the Logistic Regression model in identifying drug users, with lower false positives and better recall. Overall accuracy is 98%.

Comparison: Both models perform similarly well in identifying non-drug users, with high precision, recall, and F1-scores around 98%. The Decision Tree model outperforms the Logistic Regression model in predicting drug users, showing higher precision (43% vs. 27%), recall (38% vs. 50%), and F1-score (40% vs. 35%). Despite these improvements, both models struggle with accurately identifying drug users compared to non-users, as indicated by lower precision and recall for class 1.

Model Selection:
Logistic Regression: Better for applications where correctly identifying non-users is crucial, and missing some heroin users is acceptable. Decision Tree: Slightly better for identifying heroin users, though still not optimal, and might be considered if the cost of false positives is lower than false negatives.
Balancing Classes: Both models suffer from class imbalance, which significantly affects their ability to predict heroin users. Techniques such as oversampling the minority class (heroin users), undersampling the majority class (non-heroin users), or using synthetic data generation methods like SMOTE can help balance the dataset.

## Conclusion



### Built With


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Sandip Patel -  patelsandy1981@hotmail.com

Project Link: [https://github.com/sunnpa13/CapstoneProject](https://github.com/sunnpa13/CapstoneProject)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Citation

@misc{drug-consumption-classification-analysis,
    author = {mexwell, Deepak},
    title = {Drug Consumption Classification Analysis},
    publisher = {Kaggle},
    year = {},
    url = {https://www.kaggle.com/datasets/mexwell/drug-consumption-classification}
}

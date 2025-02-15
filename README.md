# Health-Analytics-Enhancing Health Systems Through Data Science: An Analysis of Electronic Health Records (EHRs):
## Project Overview 
This Project Looks at the health care system and explores how data Science Techniques such as Predictive modeling , Clustering and Dimentionality reduction can be used to improve healthcare resource allocation and patient outcomes 
## Reflection 
My journey diving into health systems science has greatly deepened my understanding of the complexities within healthcare delivery. I’ve come to realize just how much social factors, like where someone lives or their economic status, can impact their access to care and health outcomes.
Developing an entrepreneurial mindset in healthcare requires a dual focus on both technical and an understanding of the human side of health systems. This means finding ways to use technology and data to improve patient access and address gaps in care.
Combining data with community-driven initiatives can make a real difference in reducing healthcare disparities. I've learned that health systems require a holistic, multidisciplinary approach, inspiring me to think of myself as an innovator in healthcare, looking for ways to improve healthcare delivery and patient experiences.
I've discovered how data science can support integrated care models, improve population health, and reduce disparities. While data and technology provide powerful tools, solutions must address real-world barriers that patients face.
## Objectives
 - Explore the role of Data in Health sciences
 - indetify patterns in utilisation of health care resourses 
 - Use Predicvtive models to assess patient risk factors and improve outcomes
 - Apply clustering techniques to segment patients for targeted interventions.
 - Visualise disparities 
## Structure 
📜 README.md (Overview)
📜 dataset.csv 
📜 Script
📜 Detailed report with findings
## Tech Stack and Tools 
- Programming : Python (Pandas, Numpy , Matplotlib , Seaborn , Scikit- Learn )
- Data Visualisation : Matplotlib , Seaborn
- Machine Learning : Scikit-learn (PCA , K-means , Regression , Classification )
## Data Description
The dataset has 42 columns and 4,084 entries, capturing various demographic, medical, and healthcare usage information.
Demographic data – Age, Race, sex The Hierarchical Condition Category (HCC) score- patient’s overall health risk Average Length of Stay (LOS)- hospital stay duration Healthcare resource utilization – visits to the ER, hospital outpatient visits, skilled nursing facility (SNF) use, and home health services, Enrolment Months, Total Claims and Labs
## Data Cleaning and Preparation 
To Evaluate the quality of the Data and Prepare data for analysis
I focused on completeness of the by identifying missing values, I then Imputed the missing values using Imputation with the median for numerical columns in the attempt to reduce the influence of outliers. I made use of the SimpleImputer with the median from scikit-learn.
## Data Visualisation 
Matplotlib , Seaborn
## Insights 
A Histogram was used to examine age distributions; the age distribution is right skewed with most patients being elderly

A Scatter plots was used to investigate the relationships between the variables (HCC scores and claims) which informs the utilisation of healthcare, Patients with higher scores have higher healthcare claims

Heatmaps to visualize correlations among numerical variables,Variables showed strong correlations which could mean that the information is repetitive.

Dimentionality Reduction : PCA reduces 43 variables to 3 principal components  
## Ethical Considerations & Data Privacy
Working with electronic healthcare records (EHRs) comes with the responsibility to protect sensitive patient information. The POPI act Further stipulates this.
Data breaches can have serious consequences for the individuals and organizations. With increased use of technology to enhance healthcare it is important to consider and set in data security and safeguarding Practices
## Contact
 LinkedIn: linkedin.com/in/gomolemo-tshepiso-komane-0b0b6715a 
 Email:gomolemotkomane@gmail.com 

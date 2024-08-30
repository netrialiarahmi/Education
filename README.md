# **Analysis of Education in Indonesia: Dynamics of Education Quality and Various Policies**
![Education Image](https://raw.githubusercontent.com/netrialiarahmi/Education/main/edu.png)

### **⛳ Education Analysis in Indonesia ⛳**

### **📌 Problem Statement**<a class="anchor" id="0"></a>

Improving education quality is one of Indonesia’s most significant challenges. As an archipelagic country, Indonesia faces disparities in educational infrastructure, leading to uneven education quality across regions. This study aims to provide a comprehensive analysis of the educational landscape across provinces and offer sustainable policy recommendations to enhance the national education system.

The dataset, sourced from the Indonesian Badan Pusat Statistics (BPS) from 2013-2023, will be analyzed using various statistical methods, including:

- **Education Index**: Measures education levels based on key indicators.
- **K-Means Clustering**: Groups provinces with similar educational characteristics.
- **Sentiment Analysis**: Assesses public perception of education policies through social media data.
- **Wordcloud**: Visualizes key terms in education discussions.


### **📌 Goals**

The primary goal is to **develop data-driven policy recommendations** to **enhance the quality of education** across Indonesia. Achieving this goal will help reduce educational disparities and improve access and quality of education nationwide.

### **📌 Objectives**

- **Data Analysis and Predictive Modeling**: Use predictive models to understand and map education quality across provinces.
- **Policy Recommendations**: Provide specific and relevant policy recommendations for each province based on the analysis results.
- **Infrastructure Improvement**: Identify regions needing educational infrastructure enhancements.
- **Educational Equity**: Develop strategies to reduce educational disparities between regions.

### **📌 Metrics of Success**

- **Prediction Accuracy**
    - The accuracy (RMSE) of predictive models in estimating education quality, measured as the percentage deviation from actual values.

- **Policy Impact**
    - The impact of policy recommendations on improving education quality, measured through post-implementation evaluations.

- **Equity Improvement**
    - Reduction in educational disparities between regions, measured through comparisons of education indices before and after policy implementation.

### **📌 Challenges & Opportunities**

- **Challenges**: Significant regional disparities, data limitations, and infrastructure challenges in remote areas.
- **Opportunities**: Using historical data to create accurate predictive models, providing data-driven policy recommendations, and strengthening education quality across Indonesia.
___

### **📊 Education Index by Province in Indonesia**
![Figure 1. Education Index](https://github.com/user-attachments/assets/94dc3fa6-cac4-4066-bf76-da09ad616dea)

The graph and map of the education index distribution in Indonesia for 2023 provide a clear picture of educational disparities across provinces. According to the data presented, D.I. Yogyakarta has the highest education index, while Papua has the lowest. This analysis delves deeper into the education index by province, significant inter-provincial differences, and the factors affecting the quality of education in Indonesia.

#### **Highest and Lowest Education Index**
![Figure 2. Education Index](https://github.com/user-attachments/assets/48372b38-b539-4836-96e5-3f2ffc2340e7)

The education index in Indonesia reflects significant differences between provinces. D.I. Yogyakarta tops the list with an education index of around 75, possibly due to the presence of leading educational institutions, high literacy rates, and a strong educational culture. Conversely, Papua ranks lowest with an education index of approximately 53, indicating significant challenges in the education sector, including inadequate infrastructure, geographical difficulties, and limited resources.

The stark difference between the highest and lowest education index provinces highlights the need for addressing disparities through improvements in infrastructure, teacher training, and specialized educational programs for remote areas. Besides Yogyakarta, other provinces with high education indices include DKI Jakarta, Maluku, Aceh, and East Kalimantan. Meanwhile, provinces such as Central Java, Bangka Belitung, West Papua, and West Kalimantan also require more attention to enhance the quality of education.

#### **Geographical Distribution of the Education Index in Indonesia**
![Figure 3. Education Index](https://github.com/user-attachments/assets/e2859f5d-880a-4b1e-90ba-8c1e38b63246)

The geographical distribution of the education index reveals that provinces with high education indices are generally located in the western part of Indonesia, which is economically and infrastructurally more advanced. In contrast, provinces with low education indices are often found in the eastern part of Indonesia, such as Papua and West Papua, which are remote and underdeveloped. This geographical analysis shows that regions more advanced in education tend to have better access to educational facilities, resources, and qualified teachers. Regions with lower education indices often face challenges related to access, infrastructure, and availability of educational resources.

In this context, local regulations and community culture play a crucial role in influencing the quality of education. In some regions, progressive local policies in education, such as adequate education budget allocations, compulsory education policies, and teacher quality improvement programs, can enhance the education index. For example, D.I. Yogyakarta and DKI Jakarta have local regulations supporting education, ranging from local curriculum development to scholarship programs for outstanding students.

---

### **🧑‍🏫 Teacher-Student Ratio by Province in Indonesia**
![Figure 4. Teacher-Student Ratio Distribution](https://github.com/user-attachments/assets/2bd7fcb8-c37d-4d24-a94b-a42033c71c89)

The graph and map of the teacher-student ratio distribution in Indonesia for 2023 show significant differences between provinces in terms of the number of teachers compared to the number of high school or equivalent students. This ratio is a critical indicator of education quality, as a lower teacher-student ratio generally reflects more individual attention to students, which in turn can enhance the quality of learning.

#### **Provinces with the Highest and Lowest Teacher-Student Ratio in Indonesia**
![Figure 5. Teacher-Student Ratio Barchart](https://github.com/user-attachments/assets/1c7237c5-8c00-4f0c-a55e-80bcc4226737)

Provinces with the highest teacher-student ratios indicate that more teachers are available for each student, ideally reflecting more individual attention and potential for better education quality. According to the data, Aceh has the highest teacher-student ratio, followed by West Nusa Tenggara, North Maluku, Maluku, and D.I. Yogyakarta. This suggests that in these provinces, there is a relatively high number of teachers available for each student, which could lead to better education quality.

On the other hand, provinces with the lowest teacher-student ratios indicate a shortage of teachers relative to the number of students, signaling challenges in providing adequate attention to each student. Provinces with the lowest teacher-student ratios include West Java, Banten, DKI Jakarta, Bangka Belitung, and Bali. These provinces may face challenges in providing a sufficient number of teachers to serve the existing student population.

#### **Geographical Distribution of Teacher-Student Ratios**
![Figure 6. Teacher-Student Ratio Heatmap](https://github.com/user-attachments/assets/1c8f1bf1-9ab9-445d-8579-ef6d7fbd0747)


The geographical distribution of teacher-student ratios shows uneven distribution in terms of the number of teachers per student across Indonesia. Provinces with high teacher-student ratios are generally located in the western and central parts of Indonesia, such as Aceh and West Nusa Tenggara. Conversely, some provinces in the eastern and western parts of Indonesia, such as West Java and DKI Jakarta, have lower ratios.

This geographical analysis shows that regions with better teacher-student ratios tend to have better access to qualified teachers and educational facilities. Conversely, regions with lower ratios may face challenges in teacher recruitment and equitable distribution of teaching staff. Geographic, economic, and infrastructural challenges also play a significant role in the distribution of teacher-student ratios.

---

### **📈 Correlation between Teacher-Student Ratio and Education Index**

![Figure 7. Teacher-Student Ratio vs. Education Index](https://github.com/user-attachments/assets/a4ac064a-a420-4e61-ae39-2fda7b5ea317)

The comparison chart between the teacher-student ratio and the education index across provinces in Indonesia shows an important correlation between these two indicators. A lower teacher-student ratio generally reflects more individual attention to students, which can positively impact the education index. However, this correlation is not always linear, as other factors such as teacher quality, educational infrastructure, and local policies also play a crucial role.

#### **Impact of Teacher-Student Ratio on the Education Index**

Data analysis shows that provinces with higher teacher-student ratios, such as Aceh and West Nusa Tenggara, also have relatively good education indices. The high teacher-student ratio in these provinces indicates that each student receives more attention from teachers, which can enhance learning quality and, in turn, improve the education index.

Conversely, provinces like DKI Jakarta and West Java, despite having better infrastructure and access to more educational resources, show lower teacher-student ratios. This may be due to the high number of students in these provinces not being matched by the available number of teachers, thus lowering the ratio. However, because of the high teacher quality and available educational facilities, the education index in these provinces remains good.

#### **Variations Across Provinces in the Relationship between Teacher-Student Ratio and Education Index**

Not all provinces show a strong relationship between the teacher-student ratio and the education index. For example, North Maluku and Maluku have high teacher-student ratios, but their education indices are not as high as other provinces. This indicates that besides the teacher-student ratio, other factors such as education quality, local education policies, and the availability of educational facilities also significantly impact the education index.

On the other hand, provinces like D.I. Yogyakarta and DKI Jakarta have very high education indices despite not having as high teacher-student ratios as other provinces. This shows that teacher quality, a good curriculum, and effective education policies also significantly contribute to the high education index in these provinces.
___
### **📚 Education Participation Rates in Indonesia**

![Figure 8. K-Means Clustering Results](https://github.com/user-attachments/assets/027b6072-fd37-4d9e-80ac-e245ddfcd514)

This section discusses the education participation rates across Indonesia and applies clustering techniques to group regions based on participation characteristics in each province. The clustering is based on variables such as School Participation Rate (SPR) by age, the percentage of the population over 10 years old who have never attended school, Pure Participation Rate (PPR) by education level, and the average years of schooling. Using K-Means clustering, the provinces in Indonesia are grouped into four clusters based on school participation rates. The scatter plot shows that one cluster has only one member, indicating a significant distance from other points.

---
![Figure 9. Map of Education Participation Clusters in Indonesia](https://github.com/user-attachments/assets/b6539dca-8839-485a-a8dc-efc34cd2d7c4)


The map displays each province based on the clustering results. The table below provides a clearer view of the provinces in each cluster. The table also shows that Cluster 1 consists of only one province, Papua.

**Cluster Groupings:**

| **Cluster** | **Provinces**                                                                                                                                                                                                 |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **0**       | Sumatera Utara, Sumatera Barat, Riau, Jambi, Bengkulu, Sulawesi Tenggara, Kep. Riau, Sulawesi Tengah, Sulawesi Utara, Kalimantan Utara, Papua Barat                                                          |
| **1**       | Papua                                                                                                                                                                                                         |
| **2**       | Maluku, Kalimantan Timur, Nusa Tenggara Barat, Aceh, DKI Jakarta, DI Yogyakarta, Bali                                                                                                                         |
| **3**       | Kalimantan Tengah, Kalimantan Selatan, Nusa Tenggara Timur, Jawa Tengah, Jawa Barat, Banten, Sulawesi Selatan, Kep. Bangka Belitung, Gorontalo, Sulawesi Barat, Lampung, Sumatera Selatan, Kalimantan Barat, Jawa Timur |


The table below presents the average values for the four clusters that have been created. The comparison is made by ranking the clusters for each variable, providing a detailed view of the characteristics of each cluster.

| **Variable** | **Cluster 0** | **Cluster 1** | **Cluster 2** | **Cluster 3** |
|--------------|---------------|---------------|---------------|---------------|
| School Participation Rate (Age 7-12) | 99.24 | 83.61 | 99.5 | 99.18 |
| School Participation Rate (Age 13-15) | 96.36 | 80.91 | 98.11 | 94.51 |
| School Participation Rate (Age 16-18) | 78.34 | 64.15 | 81.13 | 70.85 |
| School Participation Rate (Age 19-24) | 28.51 | 23.89 | 33.38 | 25.46 |
| % of Population Aged 10+ Never Attended School | 2.14 | 28.51 | 2.44 | 2.88 |
| Pure Participation Rate (Elementary School) | 100.48 | 98.83 | 99.98 | 99.76 |
| Pure Participation Rate (Junior High School) | 100.68 | 101.4 | 97.66 | 103.61 |
| Pure Participation Rate (Senior High School) | 111.71 | 97.76 | 101.8 | 106.95 |
| Pure Participation Rate (University) | 134.41 | 87.72 | 110.64 | 132.22 |
| Average Years of Schooling | 9.7 | 7.34 | 9.97 | 8.75 |

The analysis reveals that Cluster 2 has the highest education participation rates across all age groups compared to other clusters. However, this cluster shows slightly lower Pure Participation Rates (PPR) by education level, with the PPR for Junior High School being the lowest among all clusters. Provinces in Cluster 2 include Jakarta, Yogyakarta, Bali, and Aceh.

Conversely, Cluster 0 exhibits moderate School Participation Rates (SPR) and the highest PPR, indicating this cluster excels in pure participation at each education level. However, this cluster also has a higher percentage of the population aged over 10 years who have attended school compared to other provinces, suggesting that many residents in these provinces are enrolled in education. Provinces with these characteristics include West Papua, Central Sulawesi, and Riau.

Cluster 3 represents a unique cluster reflecting a moderate educational situation. This cluster is characterized by moderate SPR, PPR, percentage of those who have never attended school, and average years of schooling. This cluster occupies a middle position, meaning it does not show the highest or lowest values among other clusters. Generally, this cluster reflects a relatively stable and balanced educational situation. Provinces like West Java, East Java, Central Java, and even East Nusa Tenggara belong to this group.

Compared to other clusters, Cluster 1 has the lowest SPR by age, SPR by education level, and average years of schooling among all clusters. Additionally, the percentage of the population aged over 10 years in Cluster 1 is very high, reaching 28.51%. The low education participation in this cluster highlights the need for special attention to be given to the province of Papua.
___
### **📝 Sentiment Analysis of Public Opinion**

To understand public opinion, sentiment analysis is necessary to evaluate how government programs have been perceived. We collected 484 relevant data points from social media and other sources using the keyword "Pendidikan Indonesia." For sentiment analysis, we employed the pre-trained IndoBERT Large model from indobenchmark (indobenchmark/indobert-large-p1). This model categorizes sentiments into three types: positive, neutral, and negative. This approach enables us to gain deeper insights into public perceptions of the education system and the effectiveness of government assistance programs.

#### **Conversation Trends**

![Figure 14. Conversation Trends on X](https://github.com/user-attachments/assets/1f0e2557-646f-48e2-95a7-70f99fd93193)

The conversation trends on the X platform show a spike in activity in February, with a significant increase in June, peaking at 360 tweets. This indicates that discussions around "Pendidikan Indonesia" have been a hot topic in 2024.

**Figure 15. Top 10 Tweet Locations**

![Tangkapan Layar 2024-08-30 pukul 09 55 39](https://github.com/user-attachments/assets/45e0288c-cd6d-494b-8908-3291f92f6f0f)

The top 10 locations where the most tweets originated are led by Jakarta, accounting for 25% of the total tweets, followed by Surabaya, Bekasi, and Semarang. The remaining tweets come from East Java, West Java, and unspecified locations within Indonesia.

---

#### **Sentiment Analysis**

![Figure 16. Sentiment Comparison](https://github.com/user-attachments/assets/888ce023-3e36-48c2-8343-e172a14c3817)

The sentiment analysis results show that 454 tweets are categorized as negative, 25 as neutral, and 5 as positive. This indicates a significant amount of public dissatisfaction with the current state of education in Indonesia.


![Tangkapan Layar 2024-08-30 pukul 09 56 53](https://github.com/user-attachments/assets/65b0f858-9c26-4b25-911f-48417508d610)
![Tangkapan Layar 2024-08-30 pukul 09 57 04](https://github.com/user-attachments/assets/8049aa1a-6cfb-406a-99dc-6e7355240d53)
![Tangkapan Layar 2024-08-30 pukul 09 57 12](https://github.com/user-attachments/assets/469c8a35-1b07-4747-8116-079f91e6f4c4)

### **💬 Sentiment Analysis Insights**

Based on the four figures, the analysis reveals several key points across different sentiment categories:

- **Negative Sentiment**: A significant number of people expressed concerns about the high cost of education or rising tuition fees. The phrase "Indonesia Emas 2045" was frequently mentioned, indicating public discourse about national aspirations. Additionally, terms like "minister," "work," and "scholarship" were commonly discussed. There was notable criticism directed at Education Minister Nadiem Makarim and scholarship policies perceived as ineffective. Many tweets compared domestic scholarships with those available abroad. Overall, the public conveyed apprehensions about Indonesia’s education policy direction, emphasizing the need for better accessibility and quality, and addressing the challenges faced by the younger generation in pursuing higher education.

- **Neutral Sentiment**: Similar to the negative category, many tweets highlighted concerns over high education costs, with references to tuition fees (UKT) being unaffordable for many families. This is seen as a major barrier to accessing higher education, in contrast to the free education available at the primary and secondary levels. Criticisms were also directed at the quality of education provided, citing heavy administrative burdens on educators and the perception that some ministers do not fully understand the education system. Additionally, some tweets directly criticized government policies, particularly the Ministry of Education and its leaders, who were seen as not supporting education as a public good.

- **Positive Sentiment**: Positive tweets included support for broader and more affordable access to education for everyone. There was backing for efforts to provide low-cost or even free education, and opposition to student loans and online lending practices, with the belief that education costs should be borne by the state. There was also support for offering fair salaries to teachers and lecturers as a form of appreciation for their profession. Furthermore, there was a strong sentiment against viewing education merely as a business opportunity.


![Figure 20. Top 10 Words](https://github.com/user-attachments/assets/47a7637e-8825-4f39-b787-229072a61ce0)


The top 10 words used in tweets offer further insights. For example, in the negative sentiment category, there is significant concern over education costs and the direction of educational policies. In the neutral category, many tweets echo these concerns but with a slightly different tone, possibly influenced by the pre-trained model used for analysis. Positive sentiments are rare but emphasize support for broader and more affordable access to education, opposition to student loans, and better compensation for educators.

---

#### **Content Analysis by Sentiment**
![Tangkapan Layar 2024-08-30 pukul 09 58 15](https://github.com/user-attachments/assets/0f36b110-764c-4769-9aa7-abd36ef76907)



This figure shows an example of a negative tweet that gained significant attention. The tweet criticizes the high cost of tuition fees and the perceived inadequacy of government scholarships.
![Tangkapan Layar 2024-08-30 pukul 09 58 27](https://github.com/user-attachments/assets/b90275be-7d6e-4701-be57-a3e6a433dbec)


This figure displays an example of a neutral tweet. The tweet criticizes the rising tuition costs, mentions the administrative burden on lecturers, and indirectly critiques the Education Minister's performance. The tweet is generally sarcastic in tone.

![Tangkapan Layar 2024-08-30 pukul 09 58 44](https://github.com/user-attachments/assets/4989ec63-76db-46c8-9a65-28536baeaf4f)


This figure showcases an example of a positive tweet, expressing support for a more inclusive, fair, and equitable education system in Indonesia. The tweet focuses on access, affordability, appreciation for educators, and the state's responsibility to support a quality education system.
___
### **📋 Policy Review**

#### **Education Index**
The policies supporting the improvement of the education index include:

- **12-Year Mandatory Education**: A policy requiring all children to complete primary to upper secondary education.
- **Kartu Indonesia Pintar (KIP)**: Financial assistance for children from underprivileged families.
- **School Operational Assistance (BOS) Funds**: Financial support for schools to cover operational costs.

While these policies have successfully raised the education index in Indonesia, a new challenge has emerged: the equitable distribution of education quality. This is evident from the significant disparity in education index scores between provinces with the highest and lowest scores. Tweets also highlight the broader social and economic impacts of high education costs, such as limited job opportunities despite the significant investment required for education.

#### **Teacher-Student Ratio**
Policies related to teacher-student ratios include:

- **National Education Ministry Regulation on Ideal Ratios**: A ratio of 1:28 for elementary schools and 1:32 for junior high schools.
- **Initiative Programs**: Incentive programs for teachers serving in remote areas.

The main issue concerning the teacher-student ratio is the distribution of teachers, particularly in regions with high teacher-student ratios. Significant disparities in teacher-student ratios persist.

#### **Relationship Between Teacher-Student Ratio and Education Index**
Policies related to the relationship between teacher-student ratios and the education index include:

- **2013 Curriculum**: Emphasizes interactive learning, requiring students to be more active and teachers to act as facilitators.
- **Government Employee with Work Agreement (PPPK)**: A scheme to officially appoint honorary teachers.

Both policies are effective in addressing issues related to the education index and teacher-student ratios.

#### **Education Participation Rate**
Policies related to education participation include:

- **Kartu Indonesia Pintar (KIP)**: Financial assistance for children from underprivileged families.
- **Zonasi-based Enrollment (PPDB Zonasi)**: An enrollment system based on residential zoning.

With KIP and PPDB Zonasi, the aim is to increase school participation rates by addressing two fundamental education issues: finance and access. The analysis shows that there are four distinct groups with their own characteristics, indicating that strategies to improve the School Participation Rate (SPR) must consider the local conditions.

#### **Education Factors**
Policies related to factors influencing education include:

- **Educational Infrastructure**: Building and renovating school facilities.
- **Teacher Welfare**: Increasing teacher salaries and benefits to boost motivation and teaching quality.
- **Teacher Training and Development**: Enhancing professional competencies.
- **Kartu Indonesia Pintar (KIP)**: Financial assistance for children from underprivileged families.

Despite numerous policies aimed at improving the quality of education in Indonesia, their impact has not yet been significantly observed.

#### **Public Opinion**
The majority of public opinion highlights Minister of Education Regulation No. 2 of 2024, which has led to an increase in tuition fees (UKT). Most of the public's comments are negative regarding this issue. Additionally, there are concerns about rising education costs, education policy management, and the improvement of education quality. The public hopes for systemic improvements within the Ministry of Education and Culture down to local education offices, and a review of policies perceived as detrimental and unbeneficial to the community.


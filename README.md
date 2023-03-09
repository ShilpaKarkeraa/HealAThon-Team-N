# HealAThon-Team-N
Wacky Ideators - Renal Care for Womens Health - UTIs


**Background:**
The urinary tract is made up of the bladder, ureters, urethra, and kidneys, and UTIs can occur anywhere along this tract. However, most UTIs occur in the lower urinary tract, which includes the bladder and urethra. Women are more likely to develop UTIs than men because their urethra is shorter, making it easier for bacteria to enter the bladder. In addition, a woman's urethra is located closer to the anus, which can increase the risk of bacterial contamination.

Urinary tract infection (UTI) is a common emergency department (ED) diagnosis, especially in women, with reported high diagnostic error rates. Because a urine culture, part of the gold standard for diagnosis of UTI, is usually not available for 24–48 hours after an ED visit, diagnosis and treatment decisions are based on symptoms, physical findings, and other laboratory results, potentially leading to overutilization, antibiotic resistance, and delayed treatment. Previous research has demonstrated inadequate diagnostic performance for both individual laboratory tests and prediction tools.

**Some common symptoms of UTIs in women include:**
1. A strong, persistent urge to urinate
2. A burning sensation when urinating
3. Passing frequent, small amounts of urine
4. Cloudy or strong-smelling urine
5. Pain in the lower abdomen or back
6. Feeling tired or shaky

**Objective:**

Our aim, was to train, validate, and compare machine-learning based predictive models for UTI in a large diverse set of ED patients.


**Dataset:**

Single-center, multi-site, retrospective cohort analysis of 80,387 adult ED visits with urine culture results and UTI symptoms expanded to 220 attributes. You will find the raw dataset here: https://drive.google.com/file/d/1cZELC8VivTegNDKi3Ygp2rbzxaCxmVQB/view?usp=share_link


**Steps of Implementation:**
![image](https://user-images.githubusercontent.com/90405126/224066513-57574cd5-4e6b-498a-bdcb-1f0ac9023e12.png)


**Algorithms Implemented:**
1. XGBoost Classifier offers accuracy of **84.48%**
2. LGBM Classifier offers accuracy of **84.46%**
3. Logistic Regression offers accuracy of **83.80%**
4. Random Forest Classifier offers accuracy of **82.23%**

![image](https://user-images.githubusercontent.com/90405126/224119413-3100429c-7686-4663-ad5c-6a81f171fe56.png)


**Consumer Use Cases:**
1. Hospitals and clinics: Healthcare facilities can use UTI detection systems to screen patients for UTIs. This can help to quickly identify patients who may require treatment and prevent the spread of infections.
2. Home testing: UTI detection systems can also be used at home by individuals who suspect they may have a UTI. This can provide a quick and convenient way for people to monitor their health and seek treatment if necessary.
3. Nursing homes and assisted living facilities: Residents in long-term care facilities are at a higher risk for UTIs due to underlying medical conditions and age-related changes. UTI detection systems can be used in these settings to monitor residents and detect infections early.
4. Women's health clinics: UTIs are more common in women than men due to differences in anatomy. Women's health clinics can use UTI detection systems to screen patients for UTIs and provide appropriate treatment.
5. Research studies: UTI detection systems can be used in research studies to collect data on the prevalence and incidence of UTIs, as well as risk factors and treatment outcomes. This can help to improve our understanding of UTIs and inform the development of new treatment options.


UTIs are more common in women than in men. According to the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK), more than 50% of women will have at least one UTI in their lifetime, and many will have multiple UTIs.UTIs can have serious consequences for women. If left untreated, UTIs can lead to kidney infections, which can cause permanent damage to the kidneys. UTIs can also cause premature labor in pregnant women.


**Final video:**
https://drive.google.com/file/d/13zRcrxtzX3mA7qkVbd5e9dRA9S0wmgCk/view?usp=sharing


**Conclusion:**

The best performing machine learning algorithm, XGBoost, accurately diagnosed positive urine culture results, and outperformed previously developed models in the literature and several proxies for provider judgment. Future prospective validation is warranted!

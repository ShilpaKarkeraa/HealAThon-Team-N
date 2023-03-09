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

Single-center, multi-site, retrospective cohort analysis of 80,387 adult ED visits with urine culture results and UTI symptoms expanded to 220 attributes. You will find the raw dataset here: https://drive.google.com/file/d/1cZELC8VivTegNDKi3Ygp2rbzxaCxmVQB/view?usp=sharing


**Steps of Implementation:**
![image](https://user-images.githubusercontent.com/90405126/224066513-57574cd5-4e6b-498a-bdcb-1f0ac9023e12.png)


**Algorithms Implemented:**
1. XGBoost Classifier offers accuracy of **84.48%**
2. LGBM Classifier offers accuracy of **84.46%**
3. Logistic Regression offers accuracy of **83.80%**
4. Random Forest Classifier offers accuracy of **82.23%**


**Conclusion:**

The best performing machine learning algorithm, XGBoost, accurately diagnosed positive urine culture results, and outperformed previously developed models in the literature and several proxies for provider judgment. Future prospective validation is warranted!

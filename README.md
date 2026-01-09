# Gender Disparities in Weight Perception among U.S. Adults
### : A Propensity-Matched Analysis using NHANES 2017-2018 Data

## 1. Background
In public health, the discrepancy between actual Body Mass Index (BMI) and self-perceived weight status is a known phenomenon. However, it is debated whether this discrepancy is driven by biological differences or sociocultural pressures.

## 2. Objective
To determine whether gender influences self-perceived overweight status when **actual BMI is identical**, utilizing a 1:1 matching technique to control for confounding variables.

## 3. Methods
* **Data Source:** NHANES 2017-2018 (CDC), n=5,727 (Pre-matching).
* **Study Design:** Cross-sectional study with **1:1 Nearest Neighbor Matching**.
* **Statistical Analysis:**
    * **Matching:** To eliminate BMI differences, we matched each male subject with a female subject having the nearest BMI value (Euclidean distance).
    * **Balance Check:** T-test was used to verify no significant difference in BMI between groups after matching.
    * **Outcome Analysis:** Chi-square test to compare the prevalence of self-perceived overweight status.

## 4. Key Findings (Results)
**1) Balance Check (Success)**
Before matching, BMI differed significantly between genders (P < 0.001). After 1:1 matching (n=2,769 pairs), there was **no statistical difference in BMI** between men and women (P = 0.996).

**2) Perception Gap (Significant)**
Even with identical BMI profiles, a substantial gender gap remained:
* **Perceived as Overweight:**
    * Women: **55.7%**
    * Men: **43.2%**
* **Statistical Significance:** P < 0.001 (Chi-square test)

## 5. Conclusion
This study provides robust evidence that **body image distortion in women is independent of actual body mass**. By strictly controlling for BMI, we demonstrated that women are **12.5% points more likely** to perceive themselves as overweight than men of the exact same physique. This suggests strong sociocultural influences on weight perception among U.S. women.

---
*Author: Wonil Koh, KMD, Ph.D.*
*Tools: Python (Pandas, Scikit-learn, Scipy)*
*Contact: wkoh1231@gmail.com*

# 🌍 World Happiness Analysis

## 📌 Introduction
The World Happiness Report provides a comprehensive view of global well-being. This project explores what truly drives happiness across countries and whether money alone is sufficient, or if social and structural factors play a greater role.

The goal is to derive actionable insights and suggest policies that can improve national well-being.

---

## 🧠 Assumptions

1. This analysis is **materialistic**, focusing only on measurable variables and excluding spiritual or subjective dimensions.
2. Primary research question:
   > *What truly drives happiness across countries, and where is the best place to live over time?*
3. Sub-questions (RQ1–RQ10) guide the analysis:
   - RQ1: What factors most strongly influence happiness globally?
   - RQ2: Has global happiness improved or declined over time?
   - RQ3: Which countries consistently rank in the top 10—and why?
   - RQ4: Are richer countries always happier?
   - RQ5: Which region offers the best-balanced life?
   - RQ6: Which is the best place to stay?
   - RQ7: Which countries break the rule?
   - RQ8: Which continents offer a better life evaluation?
   - RQ9: Which countries are happy vs volatile?
   - RQ10: What factors determine whether a nation is happy?

---

## 📊 Dataset

- Source: https://www.worldhappiness.report/ed/2026/
- Total entries: **2116**
- Data types:
  - 10 float columns
  - 2 integer columns
  - 1 categorical column

---

## 🧹 Data Preprocessing

- Identified missing values across multiple columns
- Applied:
  - Row filtering for meaningful data
  - Median imputation for numerical columns
- Result:
  - Dataset refined to **0 null values**

---

## ⚙️ Analysis Process

Each research question (RQ1–RQ10) is analyzed sequentially using:
- Correlation analysis
- Trend visualization
- Regional comparison
- Outlier detection
- Feature importance modeling

---

## 📈 Findings

### 🔹 RQ1: Key Drivers of Happiness
- Social Support → **0.70**
- GDP per capita → **0.68**
- Health → **0.66**

📌 Insight:
> Social support is the strongest determinant of happiness, surpassing economic wealth.

---

### 🔹 RQ2: Happiness Trend Over Time
- 2019–2021 → Growth 📈  
- 2021–2023 → Decline 📉  
- 2023–2025 → Strong Recovery 🚀  

📌 Insight:
> Global happiness shows resilience with a long-term upward trend.

---

### 🔹 RQ3: Top Countries
- Dominated by Nordic nations
- Strong in:
  - Social support
  - Freedom
  - Governance

---

### 🔹 RQ4: Are Richer Countries Happier?
- Positive correlation (**0.68**)  
- But:
  - Outliers exist
  - Diminishing returns after a threshold

📌 Insight:
> Money contributes to happiness, but is not sufficient.

---

### 🔹 RQ5: Best Balanced Region
- 🥇 Oceania  
- 🥈 Europe  
- 🥉 North America  

📌 Insight:
> Balance across health, social support, and freedom defines well-being.

---

### 🔹 RQ6: Best Countries to Live
Top countries:
- Finland
- Denmark
- Iceland
- Norway

📌 Insight:
> Strong policies, education, and social systems drive happiness.

---

### 🔹 RQ7: Outliers (Breaking the Rule)
- High GDP but low happiness: **Türkiye**
- Low GDP but high happiness: **Guatemala**

📌 Insight:
> Happiness depends on more than economic strength.

---

### 🔹 RQ8: Regional Life Evaluation
- Oceania → Highest  
- Europe → Strong  
- Asia → Lowest  

📌 Insight:
> Population pressure, governance, and inequality affect outcomes.

---

### 🔹 RQ9: Stability vs Volatility
- Stable countries → Consistent happiness  
- Volatile countries → Fluctuating well-being  

---

### 🔹 RQ10: What Defines Happiness?
Top contributors:
- Social Support  
- Health  
- Societal Stability  

📌 Insight:
> Happiness is multidimensional—not purely economic.

---

## 🧾 Conclusion

- Oceania and Europe lead global happiness rankings  
- Social support and health outweigh GDP in importance  
- Economic growth alone does not ensure well-being  

### 🧠 Final Insight:
> “The happiest nations invest in people, not just economies.”

---

## ⚠️ Limitations

- Potential bias in global reporting systems  
- Western-centric evaluation frameworks  
- Cultural differences not fully captured  

---

## 🚀 Policy Recommendations

- Strengthen social support systems  
- Improve healthcare access  
- Reduce corruption  
- Balance economic growth with well-being  

---

## 📌 Final Thought

> Happiness is not just about wealth—it is about relationships, health, and stability.

---

## Author
Sibankar Saha

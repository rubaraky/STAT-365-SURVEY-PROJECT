# STAT 365 Term Project: Analysis of University Students' Beliefs and Metaphysical Practices

##  Project Overview
This project investigates the relationship between university students' self-identified belief labels (e.g., Theist, Atheist, Deist) and their engagement in various metaphysical practices (e.g., Prayer, Law of Attraction, Fate). 

Using a dataset collected via a survey of 100+ METU students conducted by our project team, the study aims to understand:
1.  **Consistency:** Do students' practices align with their religious labels?
2.  **Hybridization:** Are students mixing traditional religious habits with modern spiritual concepts?
3.  **Demographics:** How do factors like gender and distance from family influence value changes?

##  Dataset
The analysis is based on `df_easy.csv`, which contains survey responses from university students.
- **Sample Size:** N > 100
- **Key Variables:**
    - *Demographics:* Gender, Department, High School Type, Family Socio-economic Status.
    - *Belief Identity:* Theist, Atheist, Deist, Agnostic, Pantheist.
    - *Metaphysical Practices:* Prayer, Fate, Divine Justice, Reincarnation, Law of Attraction, Soul.
    - *University Experience:* Questioning levels, Exposure to different views, Existential anxiety.

##  Methodology & Technologies
The project utilizes **Python** for data cleaning, statistical analysis, and visualization.

### Libraries Used
* `pandas` & `numpy`: Data manipulation and preprocessing.
* `scipy.stats`: Statistical hypothesis testing (Chi-Square, ANOVA, Cramer's V).
* `seaborn` & `matplotlib`: Data visualization (Heatmaps, Radar Charts, Boxplots).

### Statistical Tests
1.  **Chi-Square Test of Independence:** To determine relationships between belief labels and practices.
2.  **Cramer’s V:** To measure the effect size (strength) of these relationships.
3.  **ANOVA:** To compare "Traditional Religiosity" and "Modern Spirituality" scores across groups.
4.  **Correlation Analysis:** To explore the link between family distance and value transformation.

##  Key Findings
The analysis revealed a trend of **"Belief Hybridization"** rather than strict adherence to dogmatic categories:

* **The "Deist Paradox":** 41.7% of Deists still engage in prayer and believe in fate, suggesting "Deism" acts as a distancing mechanism from organized religion rather than a rejection of spirituality.
* **Secular Spirituality:** 35% of Atheists and 42.3% of Agnostics believe in the **Law of Attraction**, indicating a shift towards secular cosmic order concepts.
* **The Agnostic Dilemma:** 30.8% of Agnostics pray, likely as a psychological coping mechanism or cultural habituation.
* **Pantheistic Synthesis:** Pantheists scored highest in modern spiritual concepts (Law of Attraction: 73.7%, Soul: 78.9%), validating their holistic worldview.

##  Visualizations
The repository includes the following generated figures:
* `belief_practice_heatmap.png`: Heatmap showing participation rates in practices by belief group.
* `belief_radar_chart.png`: Spider plot comparing the "spiritual footprint" of Theists vs. Atheists vs. Deists.
* `correlation_heatmap.png`: Influences of family and university environment on student questioning.

##  How to Run
1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install pandas numpy seaborn matplotlib scipy
    ```
3.  Run the analysis script (e.g., `analysis.py` or open the Jupyter Notebook).

## 👥 Authors & Course Info
* **Course:** STAT 365 - [Course Name, e.g., Survey Sampling / Data Analysis]
* **Institution:** Middle East Technical University (ODTÜ / METU)
* **Date:** Fall 2026

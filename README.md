# Washing Away Death: The Impact of Handwashing on Maternal Mortality

This project explores the dramatic reduction in maternal mortality rates following the introduction of handwashing practices by Dr. Ignaz Semmelweis in the 19th century. Using historical data and statistical analysis, we investigate whether this life-saving intervention had a significant impact.

## Project Files

- `Washing_Away_Death.ipynb`  
  The main analysis notebook. It includes data loading, cleaning, visualization, and a t-test to assess statistical significance.
  
- `annual_deaths_by_clinic.csv`  
  Contains annual maternal death counts by clinic, including total births and deaths per year.
  
- `monthly_deaths.csv`  
  Contains monthly maternal death data, useful for observing trends before and after handwashing was introduced.

## Key Techniques

- Data preprocessing with **pandas**
- Data visualization with **matplotlib**
- Statistical hypothesis testing using a **two-sample t-test**

## Results

- A **t-statistic of 5.512** and a **p-value of 0.0000002985** indicate a highly statistically significant decrease in maternal mortality after handwashing was introduced.
- Visualizations show a clear downward trend in mortality following the intervention.

## Conclusion

The findings strongly support Dr. Semmelweis’s hypothesis that handwashing significantly reduced maternal mortality. This analysis highlights one of the earliest examples of evidence-based medical practice.

## How to Use

1. Clone or download the repository.
2. Open `Washing_Away_Death.ipynb` in **Google Colab** or **Jupyter Notebook**.
3. Run all cells to reproduce the analysis.

---

> Inspired by historical data and real medical breakthroughs, this project showcases how simple interventions and statistical reasoning can save lives.

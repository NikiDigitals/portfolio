# A/B Test Analysis

## Description

Statistical analysis of an e-commerce A/B test evaluating whether a new webpage design improves conversion rates compared to the existing webpage.

Completed as part of the Udacity Statistics for Data Analysis Nanodegree.

---

## Project Artifacts

- 📓 [Jupyter Notebook](./notebook%20analyze_ab_test.ipynb)
- 📊 [Dataset](./ab_data.xlsx)
- 📚 Portfolio GitBook Case Study *(coming soon)*

---

## Repository Structure

```text
.
├── data/
│   └── ab_data.csv
│
├── notebook/
│   └── analyze_ab_test_results_project.ipynb
│
├── README.md
│
└── LICENSE
```

---

## Dataset

File:

```text
ab_data.csv
```

Observations:

```text
69,889
```

Variables:

| Column | Description |
|----------|----------|
| country | Visitor country |
| group | Control or Treatment |
| converted | Conversion outcome (0/1) |

Countries:

- US
- UK
- CA

---

## Environment

Python 3.x

Libraries:

- pandas
- numpy
- matplotlib

---

## Analysis Workflow

1. Data exploration
2. Probability analysis
3. Conversion rate analysis
4. Country-level analysis
5. Null hypothesis simulation
6. p-value calculation
7. Statistical conclusion

---

## Results

### Control Conversion Rate

10.53%

### Treatment Conversion Rate

15.53%

### Observed Difference

5.01%

### p-value

< 0.001

---

## Statistical Conclusion

The null hypothesis was rejected at α = 0.05.

The treatment page demonstrated a statistically significant increase in conversion rate compared to the control page.

---

## Reproduction

Open:

```text
analyze_ab_test_results_project.ipynb
```

Run all notebook cells sequentially.

---

## License

Educational portfolio project.

---

## Author

Nicolette Martine Langendam

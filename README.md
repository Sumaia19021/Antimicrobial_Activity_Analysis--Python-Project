# Antimicrobial_Activity_Analysis-Python-Project

This repository presents a comprehensive analysis of the antimicrobial effects of **Solanum Extract** compared to the standard antibiotic **Cefuroxime** against three bacterial strains: *E. coli*, *P. aeruginosa*, and *S. aureus*. The **Zone of Inhibition (ZOI)** method is used to quantify and visualize antimicrobial efficacy.

---

## Key Features

-  Uses real experimental ZOI data for two antimicrobial agents
-  Generates descriptive statistics (mean, standard deviation, etc.)
-  Creates informative visualizations (bar plots and box plots)
-  Highlights comparative efficacy across bacterial strains

---

## Dataset Summary

The data includes ZOI measurements (in mm) for:

| Sample           | Bacteria        | Mean ZOI (mm) | Std. Dev. |
|------------------|------------------|---------------|-----------|
| **Cefuroxime**   | *E. coli*        | 18.0          | 1.0       |
|                  | *P. aeruginosa*  | 15.0          | 1.0       |
|                  | *S. aureus*      | 20.0          | 1.0       |
| **Solanum Extract** | *E. coli*     | 12.0          | 1.0       |
|                  | *P. aeruginosa*  | 8.0           | 1.0       |
|                  | *S. aureus*      | 10.0          | 1.0       |

---

##  Visualizations

### Zone of Inhibition Comparison Bar Plot

![Bar Plot](D:/Capture.PNG)

### Boxplot of ZOI for Extract vs Standard Drug

![Box Plot](D:/Capture2.PNG)

---

##  Requirements

Make sure you have the following packages installed:

```bash
pip install pandas matplotlib seaborn openpyxl
```

##  How to Run

1. Clone the repository:
```bash
git clone https://github.com/Sumaia19021/Antimicrobial_Activity_Analysis--Python-Project.git


```

2. Launch the Jupyter Notebook:
```bash
jupyter notebook python_project.ipynb
```

3. Run each cell sequentially to perform full analysis and generate plots.

---

## Interpretation

- **Cefuroxime** consistently showed higher ZOI values, indicating stronger antimicrobial activity.
- **Solanum Extract** exhibited moderate inhibitory effects, with the lowest ZOI against *P. aeruginosa*.
- Boxplots reveal a tight distribution, suggesting reliable experimental consistency.

---

## Future Enhancements

- Add statistical tests (ANOVA, t-tests)
- Automate export of processed results
- Convert to a web app using Streamlit

---

## License

This project is licensed under the MIT License.

---

## Author

- **Sumaia Jannat**
- GitHub:(https://github.com/Sumaia19021)

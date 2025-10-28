# MS Severity Wrangling (Public Demo)

This repo contains a **sanitized, synthetic** demonstration of my MS severity data wrangling workflow in R.

It demonstrates end-to-end preprocessing steps used in one of my dissertation research pipelines (with all personally identifiable and clinical data removed).  

---

## Workflow Highlights
- **EDSS binning** from MS20 survey responses  
- **Disease duration** calculation (years since symptom onset)  
- **MSSS lookup** demo (illustrative subset; see Roxburgh *Brain*, 2005)  
- **Cognitive scores** (SDMT and CVLT total computation)  
- **Covariate recodes** for smoking, income, education, employment, relapse, and race  
- Integration of multi-source clinical and synthetic genotype-like data  

> **Note:** No real data are included. All examples are generated programmatically in the vignette.

---

## Reproduce
Run directly in R:
```r
rmarkdown::render("vignettes/ms_severity_wrangling.Rmd", params = list(seed = 42)) 
```
The rendered HTML file will appear in the same folder.


## Repository Layout
ms-severity-pipeline/
├── vignettes/
│   └── ms_severity_wrangling.Rmd    # Main synthetic vignette
├── data/                            # Placeholder for example/simulated data
├── R/                               # Optional helper functions
└── README.md

---

MIT License © 2025 Defne Yilmaz

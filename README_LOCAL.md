# MS Severity Wrangling (Public Demo)

This repo contains a **sanitized, synthetic** demonstration of my MS severity data wrangling workflow in R.

- EDSS binning from MS20
- Disease duration
- Demo MSSS lookup (illustrative subset; cite Roxburgh 2005)
- Wrangling of SDMT and CVLT totals
- Covariate recodes (smoking, income, education, employment, relapse, race)

> No real data; all examples are synthetic and generated in the vignette.

## Reproduce
In R:
```r
rmarkdown::render("vignettes/ms_severity_wrangling.Rmd", params = list(seed = 42))


```bash
cat > LICENSE << 'EOF'
MIT License

Copyright (c) 2025 Defne Yilmaz

Permission is hereby granted, free of charge, to any person obtaining a copy
...


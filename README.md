# Hi, I'm Jackson Wilke

Data scientist and ML researcher with experience in large-scale climate modeling, civic data, and scientific computing.

## Education

**University of California, San Diego** — M.S. Data Science (Expected June 2027)

**University of California, Los Angeles** — B.S. Atmospheric & Oceanic Sciences and Mathematics (June 2024)

## Projects

**jem-samudra-coupler** *(In Progress)* — Adapter package that couples a JAX-based atmospheric general circulation model ([JCM](https://github.com/climate-analytics-lab/jax-gcm)) with a PyTorch neural ocean emulator ([Samudra](https://github.com/suryadheeshjith/Samudra)) through the [JEM](https://github.com/climate-analytics-lab/jax-esm) coupling framework. Handles cross-framework data exchange (JAX ↔ PyTorch), grid regridding between spectral T106 and OM4 tripolar grids, and physical variable mapping for heat flux and wind stress boundary conditions.

**BightWatch** *(DataHacks 2026)* — Larval-stress risk-triage engine for the Southern California Bight, ranking 13 CalCOFI monitoring zones by risk of fish-larvae biological stress. Built a tolerant compound-join ETL pipeline across 72 years of CalCOFI observations, integrated real-time OISST satellite SST and BEUTI upwelling indices as post-2021 bridges, and fit supervised ML models predicting stress from physical oceanographic variables (validated against the 2014–2016 "Blob" marine heatwave). Deployed as an interactive Streamlit app with Folium-based zone maps, priority queues for field teams, and optional Gemini-powered plain-language briefings. [[App](https://nzbvtzu9v7rxdjv5jf4yng.streamlit.app/)]

**Liver Cancer Spatial Epidemiology** *(In Progress)* — ZCTA-level spatial epidemiology pipeline investigating the association between ambient PM2.5 and primary liver cancer incidence across the contiguous U.S. (2018–2022). Implemented a Multi-Constraint Monte Carlo algorithm to impute NCI-suppressed county cancer counts, then probabilistically downscaled to 19,835 ZCTAs using demographic constraints and Census API integration. Primary inference uses a Bayesian BYM2 spatial model fit via R-INLA with penalized-complexity priors; supplemented by negative binomial GAMs with 2D spatial smooths for non-linearity testing. Includes 37 sensitivity analyses covering wildfire PM2.5 decomposition, race-stratified subgroup models, lag-window sweeps, co-pollutant adjustment, and compositional race-covariate handling via isometric log-ratio transforms.

## Experience

**Graduate Researcher** — UCSD Climate Analytics Lab *(Sep 2025 – Present)*
- Building ML pipelines predicting atmospheric variables from 60+ years of climate data using PyTorch, xarray, and Dask for distributed processing of 800GB+ datasets
- Developing a coupled atmosphere–ocean model integrating a JAX-based physics atmospheric model with a PyTorch ML ocean emulator

**Data Scientist** — Hack for LA *(Aug 2024 – Sep 2025)*
- Contributed to an interactive web app mapping 12.5 million parking citations; analyzed large datasets to surface trends and actionable insights

**Undergraduate Researcher** — UCLA *(Mar 2023 – Sep 2023)*
- Applied Lagrangian particle tracking to analyze Southern Ocean currents contributing to ice shelf melting

**Undergraduate Researcher** — Salk Institute for Biological Studies *(Sep 2021 – Sep 2022)*
- Analyzed olfactory data using hyperbolic geometry and Bayesian statistics

## Skills

`Python` `PyTorch` `JAX` `Xarray` `Dask` `Streamlit` `Weights & Biases` `Hydra` `Pandas` `SQL` `R` `MATLAB`

## Awards

- **2nd Place** — UCSD SMASH & NSF HDR ML Challenge Hackathon for Coastal Flooding (2026)
- **1st Place** — Research Conference, San Diego Mesa College (2022)

## Contact

[![Email](https://img.shields.io/badge/Email-jackson.wilke8%40gmail.com-blue)](mailto:jackson.wilke8@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jackson%20Wilke-0A66C2?logo=linkedin)](https://linkedin.com/in/jackson-wilke-37827821a)

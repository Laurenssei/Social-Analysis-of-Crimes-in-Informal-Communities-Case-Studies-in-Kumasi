# Social-Analysis-of-Crimes-in-Informal-Communities-Case-Studies-in-Kumasi

📄 Full Report: [View Analysis]( .html)

## Overview
This qualitative study analyzes social factors and mechanisms perpetuating criminal activities (e.g., theft, robbery, drug abuse, assault) in Kumasi's informal settlements (Ayigya, Oforikrom, Asawase), based on 46 interviews with suspects, police, religious leaders, ex-convicts, guardians, and assembly members. Inductive thematic analysis identifies six themes—family dysfunction/parental negligence, peer-driven delinquency, community normalization of crime, social isolation, community stigma, and community mistrust—as core perpetuators, amplified by structural enablers like poverty and unemployment. 

## Objectives
- Analyze the factors and mechanisms that contribute to and perpetuate criminal activities within Kumasi’s informal settlements (Ayigya, Oforikrom, Asawase).

## Dataset Summary
- **Source**: Primary qualitative data from 46 semi-structured interviews in Kumasi's informal settlements (2025). 
- **Sample Size**: 46 respondents (suspects: 10, police officers: 13, religious leaders: 13, ex-convicts: 6, guardian: 1, assembly members: 4).
- **Key Variables**: Themes (family dysfunction, peer delinquency, community normalization, social isolation, stigma, mistrust); structural enablers (poverty, unemployment, poor infrastructure); emotional cues (distress, resignation); community dynamics (reporting, discipline).

## Methods
- Inductive thematic analysis (Braun & Clarke, 2006): Familiarization with transcripts, initial coding (e.g., “single parenting,” “drug markets”), theme generation/review (6 themes), definition/reporting.
- Cross-validation across stakeholder groups for robustness; integration with quantitative crime data (2021–2024) for contextual trends.

## Key Findings
- Family Dysfunction: Single parenting/loss (e.g., SUS001: “divorced when I was six”) and polygamy/neglect create supervisory voids, driving survival crimes (e.g., theft for food).
- Peer-Driven Delinquency: Gangs/peer pressure normalize drug abuse/robbery (e.g., SUS006: “bad company”); hotspots like “Anadwo 33d3” facilitate recruitment.
- Community Normalization: Cultural tolerance in Zongo/squatter areas enables external crimes (e.g., MV00L003: “Zongo… low education”); weak discipline (e.g., “foolish case”) reduces accountability.
- Social Isolation: Unemployment/poverty isolates youth (e.g., EX-C007: “no money… hustling”); lack of integration pushes to delinquent networks.
- Community Stigma: Settlements stereotyped as crime-prone (e.g., RL006: “degraded the statute”), reinforcing delinquent expectations.
- Community Mistrust: Police corruption/interference (e.g., MV00L002: “how much the person was able to pay”) erodes reporting, enabling perpetuation.
- Structural Enablers: Poverty/unemployment (MV00L001), poor infrastructure (RL001: “no street lights”), lack of education amplify social mechanisms.



## How to Reproduce the Analysis
### Requirements
- NVivo or manual coding software for thematic analysis; R/Python for quantitative trends.
- R (version 4.0 or higher) for visualizations.
- RStudio
- R packages: tidyverse, ggplot2, dplyr

### Steps
1. Clone this repository.
2. Use NVivo/manual coding on transcripts for themes.
3. Open `analysis.Rmd` in RStudio for quantitative.
4. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "ggplot2"))`).
5. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). Social Analysis of Crimes in Informal Communities: Case Studies in Kumasi.

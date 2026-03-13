# The Happiness Paradox: Why Income Alone Is Not the Answer

An exploratory data analysis investigating the relationship between income, spending habits, and self-reported happiness among 1,000+ residents of a simulated city.

## Overview

Conventional wisdom suggests that more money leads to more happiness. This project challenges that assumption by analyzing detailed financial and behavioral data to uncover what actually drives well-being.

### Key Findings

- **Disposable income shows no positive relationship with happiness** — trend lines are flat or slightly negative across all education levels.
- **How you spend matters more than how much you have** — residents who allocate more toward rent and food report consistently higher happiness.
- **Diminishing returns exist** — once basic needs (quality housing, adequate food) are comfortably met, additional spending yields little happiness gain.
- **Education does not cleanly predict income** — high school/college educated residents actually earn less on average than those with the lowest education level.

## Data

The analysis uses data from the [VAST Challenge 2022](https://vast-challenge.github.io/2022/), a participatory urban planning exercise involving a fictional city tracked over 15 months. The dataset includes:

| File | Description |
|------|-------------|
| `data/Participants.csv` | Demographic and background info for each resident |
| `data/FinancialJournal.csv` | Timestamped financial transactions |
| `data/ParticipantStatusLogs1.csv` | Behavioral and status logs including happiness scores |
| `data/Apartments.csv` | Housing details including rent and room count |

> **Note:** `FinancialJournal.csv` and `ParticipantStatusLogs1.csv` are too large for GitHub. Download them from [Google Drive](https://drive.google.com/drive/folders/1Tx2JAwF9iElchq4IsqKeX9lI93FNlq01?usp=sharing) and place them in the `data/` folder before running the analysis.

## Visualizations

The analysis produces four main visualizations:

1. **Income by Education Level** — Boxplots showing the distribution of weekly net income across education groups
2. **Happiness vs. Disposable Income** — Faceted scatter plots revealing the surprising negative/flat trend between income and happiness
3. **Happiness vs. Rent** — Scatter plot with grouped regression lines showing diminishing returns of rent spending on happiness
4. **Happiness by Food Budget** — Overlaid histograms demonstrating that higher food budgets are strongly associated with higher happiness

## Setup

### Requirements

- R (>= 4.0)
- R packages: `tidyverse`, `lubridate`, `scales`

### Running

Open `code.Rmd` in RStudio and knit to PDF or HTML. Required packages will be installed automatically if not already present.

## References

- Murthy, V. H. (2023). *Our Epidemic of Loneliness and Isolation*. U.S. Department of Health and Human Services.
- IEEE Visual Analytics Science and Technology (2022). *VAST Challenge 2022*.
- World Health Organization (2023). *Healthy diet*.

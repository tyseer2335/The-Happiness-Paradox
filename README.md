# The Happiness Paradox: Why Income Alone Is Not the Answer


An exploratory data analysis investigating the relationship between income, spending habits, and self-reported happiness among 1,000+ residents of a simulated city.

## Overview

Conventional wisdom suggests that more money leads to more happiness. This project challenges that assumption by analyzing detailed financial and behavioral data to uncover what actually drives well-being.

## Dataset

The analysis uses data from the [VAST Challenge 2022](https://vast-challenge.github.io/2022/), a participatory urban planning exercise involving a fictional city tracked over 15 months. The dataset includes:

| File | Description |
|------|-------------|
| `data/Participants.csv` | Demographic and background info for each resident |
| `data/FinancialJournal.csv` | Timestamped financial transactions |
| `data/ParticipantStatusLogs1.csv` | Behavioral and status logs including happiness scores |
| `data/Apartments.csv` | Housing details including rent and room count |


## Setup

Download datasets from [Google Drive](https://drive.google.com/drive/folders/1Tx2JAwF9iElchq4IsqKeX9lI93FNlq01?usp=sharing) and place them in the `data/` folder before Rmd file.

Open `code.Rmd` in RStudio and knit to PDF or HTML. Required packages will be installed automatically if not already present.

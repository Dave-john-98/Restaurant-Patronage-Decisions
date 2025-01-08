# The Impact of Online Customer Reviews on Restaurant Patronage Decisions

## Overview
This project explores the influence of online customer reviews on restaurant patronage decisions. By analyzing factors such as star ratings, written reviews, and visual content (e.g., food photos), the study aims to provide actionable insights for restaurant owners to optimize their online presence and improve customer engagement.

---

## Contents
1. [Abstract](#abstract)
2. [Research Questions](#research-questions)
3. [Methodology](#methodology)
4. [Key Findings](#key-findings)
5. [Limitations](#limitations)
6. [How to Use This Project](#how-to-use-this-project)
7. [Dependencies](#dependencies)
8. [License](#license)

---

## Abstract
This study addresses how different elements of online reviews influence restaurant patronage. Platforms like Yelp, TripAdvisor, and Google Reviews are central to customer dining decisions, yet the exact impact of reviews remains ambiguous. Through statistical analysis and simulations, this project investigates:
- The effect of star ratings on visitation scores.
- The role of positive food reviews.
- The influence of high-quality food images.

---

## Research Questions
1. **Does a higher star rating increase a restaurant's visitation score?**
2. **Do positive reviews about food increase visitation scores?**
3. **Does the presence of high-quality food images in reviews improve visitation scores?**

---

## Methodology
- **Population:** Restaurant patrons, segmented by demographics (age, location, etc.).
- **Sample Size:** 60 participants per scenario (treatment and control groups).
- **Data Collection:** Google Forms survey with mock restaurant profiles.
- **Statistical Analysis:** Simulations using R, t-tests, effect size calculations, and confidence intervals.

---

## Key Findings
- **Star Ratings:** Strong correlation with customer visitation scores.
- **Positive Reviews:** Significant impact on attracting customers.
- **High-Quality Images:** Influence varies; professional photography may enhance digital presence.

---

## Limitations
- **Biases:** Response and selection biases may affect results.
- **Causality:** Difficulty isolating review impacts from external factors like location or marketing campaigns.
- **Complexity:** Multifaceted decision-making processes may dilute the influence of reviews.

---

## How to Use This Project

### Prerequisites
- Install R and RStudio.
- Ensure required R packages are installed:
  - `data.table`
  - `ggplot2`
  - `rstatix`
  - `DT`

### Steps to Reproduce
1. Open the `Rmd` file in RStudio (`The-Impact-of-Online-Customer-Reviews-on-Restaurant-Patronage-Decisions.Rmd`).
2. Run the code chunks to simulate data and perform statistical analysis.
3. Review the results in the generated HTML report.

### Outputs
- Statistical summaries (effect sizes, p-values, confidence intervals).
- Simulated datasets.
- Visualizations of findings (e.g., bar charts, tables).

---

## Dependencies
- **Programming Language:** R
- **Packages:**
  - `data.table`
  - `ggplot2`
  - `rstatix`
  - `DT`

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

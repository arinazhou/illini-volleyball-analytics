# Illini Volleyball Performance Analytics: 2024 Season

This project provides an analytical look at the 2024 performance of the University of Illinois women's volleyball team, using real game stats to uncover patterns in player strengths, team dynamics, and lineup optimization strategies.

## Motivation

As a former national-level volleyball player, I've always believed in the power of data to improve athletic performance. This project revisits that philosophy using up-to-date team stats, focusing especially on conference games to minimize variance and yield cleaner insights.

## Dataset

- Original source: [Fighting Illini Official Stats](https://fightingillini.com/sports/womens-volleyball/stats)
- Working dataset: `data/2024_Illini_volleyball_individual_performance.csv`

## Analysis Summary

### Offensive Analysis
- **Kill Rate**: Mean = `0.29` — a strong indicator, aligning with top collegiate levels.
- **Attacking Efficiency**: Mean = `0.156`
- **Error Rate**: Mean = `0.0659`, suggesting some instability under pressure.

### Defensive Analysis
- **Successful Dig Rate**: Mean = `0.96`
- **Effective Block Rate**: Approaching `0.5` — a notable strength in defense.

### Substitutes Evaluation (Random Forest)
- Trained a Random Forest model to estimate score contribution.
- Top impactful skills: `Kills`, `Set Assists`, and `Reception Attempts`
- Less predictive skills: `Service Aces` — inviting reconsideration of training priorities.

## Key Takeaways

- The team exhibits strong offense and defense, but with moderate attacking stability.
- Substitution strategies can be improved by reevaluating players' roles based on predictive metrics, not just traditional ones.
- A data-driven approach offers actionable insights for both training programs and live-game strategy.

## Tech Stack

- Python, pandas, matplotlib, scikit-learn
- Random Forest modeling
- Radar charts and comparative stat visualizations

## Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/arinazhou/illini-volleyball-performance-analytics.git
   cd illini-volleyball-performance-analytics

## Limitations and Furture work

The current analysis is based on a relatively small and season-specific dataset, which may limit the generalizability of the findings. Future work could involve expanding the dataset across multiple seasons to validate observed trends.



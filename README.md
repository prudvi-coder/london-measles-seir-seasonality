# London Measles: Stochastic SEIR Seasonality Models

University of Michigan STATS 531 modeling project comparing traditional school-term seasonal forcing with Fourier-based transmission models using stochastic SEIR/partially observed Markov process inference.

## Focus

- Model London measles dynamics and seasonal transmission
- Estimate parameters using iterated filtering / particle-based inference
- Compare model fit, convergence, and seasonal representations

The submitted report favors the school-term model over the tested Fourier alternatives (reported AIC advantage approximately **59.8**). Results are taken from the submission, not a fresh execution.

## Files

- `report.qmd`: editable Quarto source
- `report.pdf`: submitted report
- `src/`: analysis scripts
- `figures/`, `results/`: saved outputs
- `references.bib`: bibliography

Some scripts assume an HPC environment or study-specific file paths. Review these before running. This repository is a research submission, **not an independently validated one-command reproduction**.

# Hi, I'm Alex

I'm a Data Analyst moving into data science, working full time while studying for an MSc in Computer Science with Artificial Intelligence at the University of York. My projects below focus on what makes machine learning trustworthy: pipelines that run reliably every day, models judged against a real benchmark rather than their own fit, and code that's tested and continuously integrated.

## Tools I use

| Area | Tools |
|---|---|
| **Languages** | Python · R (tidyverse) · SQL · SAS |
| **Data analysis and BI** | Power BI · SAS Enterprise Guide · tidyverse · pandas · NumPy |
| **Machine learning** | TensorFlow · Keras · statsmodels · SciPy · regression modelling |
| **Engineering** | Git · GitHub Actions CI · pytest · ruff |

## Personal Projects

### [Probabilistic Forecasting of Football Corner Counts](https://github.com/Git4AlexD/football-corners-predictor)
An automated daily data and machine learning pipeline covering 10 European football leagues. It collects market prices and results from two data sources, trains negative-binomial regression models to forecast corner counts, and evaluates the probabilistic forecasts against market closing prices with bootstrap confidence intervals. It runs on a schedule in GitHub Actions and publishes its result charts every day.

`Python` `pandas` `statsmodels` `SciPy` `pytest` `GitHub Actions`

### [Custom-Chess AI Application](https://github.com/Git4AlexD/spokebound-chess-ai)
A desktop strategy game (Spokebound) in which players design their own chess-style pieces and play against an AI opponent with ten difficulty levels. The opponent uses alpha-beta search, with its evaluation weights tuned by an evolutionary optimiser (CMA-ES) that I implemented from scratch. It is built with the Python standard library only, has a Tkinter interface and peer-to-peer online play through room codes and a relay server, and comes with an automated test suite and continuous integration on Windows.

`Python` `game AI` `evolutionary optimisation` `networking` `Tkinter` `GitHub Actions`


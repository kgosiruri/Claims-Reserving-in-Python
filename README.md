🧮 Claims Reserving in Python

An exploratory project aimed at understanding and implementing claims reserving techniques using Python.

⸻

🔍 Project Overview

This repository investigates claims reserving from both deterministic and stochastic perspectives, with and without economic assumptions. It explores core actuarial models, sensitivity testing, and real-world financial adjustments like inflation and discounting.

⸻

📌 Key Features

✅ Core Reserving Models Implemented
	•	Chain-Ladder Model
Classic deterministic method based on historical development factors.
	•	Bornhuetter-Ferguson (BF) Model
Combines a priori loss ratios with Chain-Ladder for stability in early development years.
	•	Cape Cod Model
A variant of BF that uses exposure-based weights to estimate expected losses.
	•	No-Assumptions Model
A simple baseline without economic or actuarial assumptions, to observe raw claims patterns.

⸻

🧠 Assumptions-Based Adjustments
	•	Inflation Adjustment
Applied using historical inflation data to restate nominal claim values in real terms.
	•	Discounting
Future claim payments are discounted using UK Gilt yield data to reflect time value of money.

⸻

🎲 Stochastic Modeling of Claims
	•	Frequency Models
	•	Poisson
	•	Negative Binomial
	•	Severity Models
	•	Lognormal
	•	Gamma
	•	Pareto
	•	Aggregate Claims
Total claims simulated by combining frequency and severity — applied across reserving models.
	•	Sensitivity Analysis
Testing the impact of distributional choices and economic factors on reserve estimates.

⸻

📈 Applications
	•	Understanding and comparing reserving model behavior.
	•	Visualizing development triangles and projections.
	•	Evaluating model robustness under economic stress and claim variability.
	•	Building a base for stochastic reserving extensions (e.g. Mack model, Bootstrap CL).

⸻

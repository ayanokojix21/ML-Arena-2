# Contributing to ML Arena 2

This repo contains only the Logistic Regression problem.

## Scope

- Make changes for one issue per pull request.
- Work in one track notebook per pull request.
- Do not rename notebook files or folders.

## Notebook Paths

- Exploration: `exploration/exploration.ipynb`
- Library: `library/training.ipynb`
- Scratch: `scratch/training.ipynb`
- Optimization: Use `library/training.ipynb` or `scratch/training.ipynb` based on issue scope.

## Problem Type Expectations

### Exploration

- Goal: Understand data quality, distributions, and patterns.
- Required output:
	- At least 3 meaningful visualizations.
	- 3 to 6 insight bullets tied to the plots.
	- Data quality notes (missing values, outliers, or skew).
- Avoid heavy model training unless the issue explicitly asks for it.

### Library

- Goal: Build a baseline using standard ML libraries.
- Required output:
	- Metric table using issue-specific metrics.
	- Results on train and validation/test splits.
	- Short note on preprocessing and random state.
- Keep code clear and reproducible.

### Scratch

- Goal: Implement algorithm logic from first principles.
- Required output:
	- Core algorithm written manually.
	- Training/convergence evidence (loss or cost curve) when applicable.
	- Final metric table.
- Do not use library model classes unless the issue explicitly allows it.

### Optimization

- Goal: Improve an existing library or scratch baseline.
- Required output:
	- Baseline metrics before optimization.
	- Optimized metrics after changes using the same split/seed.
	- Before vs after benchmark table and short explanation.
	- Benchmark details:
		- Required comparison: baseline metrics vs optimized metrics.
		- Required metrics: use issue-specific metrics (for example MAE/MSE/R2 or Accuracy/F1).
		- Optional but recommended: training time or inference time.
		- Add 2 to 4 bullet points explaining why performance changed.
- Prioritize measurable and reproducible improvements.

## Required in All Tracks

- Work on exactly one issue per pull request.
- Keep changes limited to the assigned notebook path.
- Run the notebook top to bottom without errors.
- Keep outputs, metrics, and plots visible.
- Use fixed random state/seed when applicable.
- Include `Closes #<issue-number>` in the pull request description.

## Workflow

1. Fork this repository on GitHub.
2. Clone your fork and enter the repo folder:

```bash
git clone https://github.com/<your-username>/ML-Arena-2.git
cd ML-Arena-2
```

3. Create a branch:

```bash
git checkout -b <track>/logistic-regression-<short-task-name>
```

4. Open the notebook in Colab, complete changes, and download the updated `.ipynb`.
5. Replace the same notebook file in local repo.
6. Commit and push:

```bash
git add exploration/*.ipynb library/*.ipynb scratch/*.ipynb
git commit -m "<clear message>"
git push origin <branch-name>
```

7. Open a pull request and include:

```text
Closes #<issue-number>
```

## Review Checklist

- Notebook runs top to bottom without errors.
- Outputs and metrics are visible.
- Explanations are short and clear.
- Track rules are followed.
- Changes are reproducible.
- For optimization issues, before vs after benchmark is included.

Keep submissions simple, focused, and readable.

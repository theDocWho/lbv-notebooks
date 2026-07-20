# Learn by Visualization — practice notebooks

Hands-on companions to the interactive explainers at
**[learn-by-visuallization.org](https://learn-by-visuallization.org/illustrated/index.html)**.

Each notebook is a set of **TODO exercises with self-checking asserts**: fill in the scaffold,
re-run the check cell, turn the ❌ into a ✅. No hidden answers — the checks define "correct".
Everything runs on free tiers: **Google Colab**, **Kaggle**, or local Jupyter (Python ≥ 3.9).

| Notebook | Phase | Pairs with |
|---|---|---|
| [ai-ml/00-python-foundations.ipynb](ai-ml/00-python-foundations.ipynb) | 0 · Python | comprehensions, generators, dunder, sorting lab |
| [ai-ml/01-numpy-pandas.ipynb](ai-ml/01-numpy-pandas.ipynb) | 1 · Scientific stack | vectorization, broadcasting, groupby, merge |
| [ai-ml/02-math-optimization.ipynb](ai-ml/02-math-optimization.ipynb) | 2 · Math | dot product, transformations, eigenvectors, optimizer race |
| [ai-ml/03-classic-ml.ipynb](ai-ml/03-classic-ml.ipynb) | 3 · Classic ML | metrics, cross-validation, k-means, bias–variance |

More phases (deep learning, transformers, LLM/RAG, MLOps) land as the explainer tracks grow.

## Conventions

- **Badges**: every notebook opens with Colab/Kaggle badges pointing at this repo (`main` branch).
- **Setup cell**: guarded installs (`pip` only if the import is missing), a seeded RNG, and a
  `check(name, fn, hint)` helper that prints PASS/FAIL and never raises.
- **CI**: `nbconvert --execute` runs every notebook top-to-bottom on push — unsolved TODOs must
  print ❌ FAIL, not crash.

## License

MIT — use them in your own courses, PRs welcome.

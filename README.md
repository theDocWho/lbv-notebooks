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
| [ai-ml/04-deep-learning.ipynb](ai-ml/04-deep-learning.ipynb) | 4 · Deep learning | activations & slopes, backprop by hand, XOR MLP from scratch (pure NumPy) |
| [ai-ml/05-nlp-transformers.ipynb](ai-ml/05-nlp-transformers.ipynb) | 5 · NLP & Transformers | TF-IDF by hand, cosine ranking, scaled dot-product attention |
| [ai-ml/06-llm-rag-agents.ipynb](ai-ml/06-llm-rag-agents.ipynb) | 6 · RAG & agents | chunking, retriever, grounded prompts, a ReAct loop (no API key) |
| [ai-ml/06b-llm-internals.ipynb](ai-ml/06b-llm-internals.ipynb) | 6B · LLM internals | BPE from scratch, temperature, top-k sampling |
| [ai-ml/07-mlops-drift.ipynb](ai-ml/07-mlops-drift.ipynb) | 7 · MLOps | baseline metrics, covariate drift, PSI monitor |

## Conventions

- **Badges**: every notebook opens with Colab/Kaggle badges pointing at this repo (`main` branch).
- **Setup cell**: guarded installs (`pip` only if the import is missing), a seeded RNG, and a
  `check(name, fn, hint)` helper that prints PASS/FAIL and never raises.
- **CI**: `nbconvert --execute` runs every notebook top-to-bottom on push — unsolved TODOs must
  print ❌ FAIL, not crash.

## License

MIT — use them in your own courses, PRs welcome.

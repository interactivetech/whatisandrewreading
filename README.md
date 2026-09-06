# What Is Andrew Reading? 📖

A focused research-paper digest curated for **Andrew Mendez** (`@interactivetech`) around architectures and agents that can learn, recur, adapt, and improve over time.

The reading list is checked **every two days**. A new digest is published only when there are genuinely new or materially updated papers worth adding; quiet runs do not create empty updates.

## Research tracks

Each full digest contains three papers in each track:

1. **Self-improving agents** — agents that accumulate experience, skills, feedback, critics, or other reusable mechanisms that improve future behavior.
2. **Looped transformers** — recurrent-depth, universal, iterative, recursive, or looped Transformer architectures that reuse computation across depth or time.
3. **Transformer architectures for continual learning** — memory, retrieval, adapters, parametric attention, fast weights, and other mechanisms for lifelong or continual adaptation.
4. **Transformer architectures for self-improvement** — self-training, test-time learning/training, online weight updates, and architectures designed to improve from their own computation or incoming context.

## Curation rules

- **Papers only.** No news, policy, blog posts, or general articles.
- Prefer genuinely new or materially revised work, then the strongest relevant recent/foundational work for the inaugural reading list.
- Each entry links to a primary paper source such as arXiv, ACL Anthology, PMLR, OpenReview, or an author project page.
- For every paper, the search also checks for an **official or author-linked GitHub repository**. A code link is included only when it can be verified; missing code links are intentionally left blank rather than guessed.
- Previously listed papers are not repeated unless a new revision or release materially changes the work.

## How the site works

This repository is intentionally static:

| Piece | What it does |
|---|---|
| `index.html` | The GitHub Pages site; no build step or model API required. |
| `data/YYYY-MM-DD.json` | One curated reading digest. |
| `data/index.json` | Lists published digests newest-first. |

Research and curation are performed by ChatGPT's scheduled research task, which searches current public sources and writes verified results to this repository. There is **no Anthropic/Claude dependency, API key, or GitHub Actions paper-generation job** in this fork.

## Hosting

Enable **GitHub Pages → Deploy from a branch → `main` → `/ (root)`** to publish the site at:

`https://interactivetech.github.io/whatisandrewreading/`

## Provenance

Forked from [thestephencasper/whatiscasreading](https://github.com/thestephencasper/whatiscasreading) and retargeted to Andrew's research interests.

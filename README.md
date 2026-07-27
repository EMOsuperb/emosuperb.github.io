# emosuperb.github.io

Project website and leaderboard for **EMO-SUPERB** (EMOtion Speech Universal PERformance Benchmark), served at [emosuperb.github.io](https://emosuperb.github.io/).

Benchmark code lives in [EMO-SUPERB-submission](https://github.com/EMOsuperb/EMO-SUPERB-submission).

## Pages

| File | Content |
|---|---|
| `index.html` | Introduction, the three fundamental SER problems, leaderboard, contribution guide |
| `typed_description.html` | How ChatGPT is used to interpret free-form typed annotations |
| `standardization.html` | Standardized, leakage-free dataset partitions for the six SER datasets |

## Paper

Open-Emotion: A Reproducible EMO-SUPERB for Speech Emotion Recognition Systems — IEEE SLT 2024, pages 510-517.
[DOI](https://doi.org/10.1109/SLT61566.2024.10832296) · [arXiv](https://arxiv.org/abs/2402.13018)

## Local preview

Static HTML with no build step:

```bash
python -m http.server 8080
```

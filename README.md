# SASRec vs LightFM: Sequential Recommendations Benchmark

Internship project at Cian (real-estate marketplace): evaluating whether a sequential model (SASRec) can outperform the production matrix-factorization baseline (LightFM).

## Task
Offline benchmark of candidate models for the recommendations feed.

## Approach
- Reproduced the production LightFM setup as a baseline
- Implemented and tuned SASRec on user interaction sequences
- Compared on held-out data with ranking metrics

## Results
SASRec improved key offline ranking metrics ~2× over the baseline.

## Stack
Python, PyTorch, pandas

## Limitations
Offline evaluation only; results were not validated in an online A/B test.

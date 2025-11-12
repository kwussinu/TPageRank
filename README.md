PageRank — An Eigenvector Problem

Recreates Google’s PageRank using only Python built-ins.

Features:

- Python code
- Handles dangling nodes 
- Adjustable damping factor α (default 0.85)
- Demo on a tiny 4-page graph
- Pretty-printed ranking with a sanity check (sum 
R ≈ 1)

Requirements:

Python 3.8+ (only standard library is used)

Quick Start:

# run the built-in demo
python3 pagerank.py

You’ll see:
the transition matrix M,
the Google matrix G,
the converged PageRank vector R,
pages sorted from most to least important.



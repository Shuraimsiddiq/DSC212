# Spectral Modularity on Zachary's Karate Club

Coursework submission for **DSC 212 (Graph Theory and Linear Algebra)** under **Prof. Saptarshi Bej**, IISER Thiruvananthapuram.

## Overview

From-scratch implementation of Newman's (2006) recursive spectral bisection method for community detection on Zachary's Karate Club network. The notebook partitions the graph using the leading eigenpair of the restricted modularity matrix, visualizes community splits on a fixed spring layout, and tracks how degree centrality, betweenness centrality, closeness centrality, and clustering coefficients evolve across iterations.

## Repository Contents

* `Assignment.ipynb` — Complete Jupyter notebook containing the implementation, step-by-step split visualizations, metric evolution plots, and final discussion.

## Dependencies

* `numpy`
* `networkx`
* `matplotlib`

## References & Acknowledgment

* Newman, M. E. J. (2006). Modularity and community structure in networks. *Proceedings of the National Academy of Sciences*, 103(23), 8577–8582.

I referred to existing solutions while working through this problem. I used Claude and Gemini to look up standard library functions, debug errors in my code, and verify my understanding of the metric analysis.

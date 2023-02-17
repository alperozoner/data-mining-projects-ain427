In this project, two frequent pattern mining algorithms were compared in terms of their memory usage and time complexity.

## Overall Conclusion of the Report
All in all, interestingly enough, two algorithms lie at the two opposide ends of the spectrum both for Memory usage and Time Complexity. Apriori is slow but uses very little memory (~couple of Kbs) but takes a very long time (~50 seconds) to compute sets with very low minsup values which are less than 0.01 (0.005, 0.004, 0.003 in our experiment). On the other hand, FP-Growth is very fast, even with minsup << 0.01, it keeps a near-constant time of around 3 to 5 seconds, but it is very memory hungry, as it used tens of megabytes of memory, which is four orders of magnitudes higher than Apriori's memory usage.

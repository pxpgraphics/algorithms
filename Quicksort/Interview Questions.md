# Quicksort Interview Questions

## 1. Nuts and bolts.
A disorganized carpenter has a mixed pile of `n` nuts and `n` bolts. The goal is to find the corresponding pairs of nuts and bolts. Each nut fits exactly one bolt and each bolt fits exactly one nut. By fitting a nut and a bolt together, the carpenter can see which one is bigger (but the carpenter cannot compare two nuts or two bolts directly). Design an algorithm for the problem that uses `nlogn` compares (probabilistically).

## 2. Selection in two sorted arrays.
Given two sorted arrays `a[]` and `b[]`, of sizes `n1` and `n2`, respectively, design an algorithm to find the `k`th largest key. The order of growth of the worst case running time of your algorithm should be `logn`, where `n=n1+n2`.

* Version 1: `n1=n2` and `k=n/2`
* Version 2: `k=n/2`
* Version 3: no restrictions

## 3. Decimal dominants.
Given an array with `n` keys, design an algorithm to find all values that occur more than `n/10` times. The expected running time of your algorithm should be linear.

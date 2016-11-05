# Mergesort Interview Questions

## 1. Merging with smaller auxiliary array.
Suppose that the subarray `a[0]` to `a[n-1]` is sorted and the subarray `a[n]` to `a[2n-1]` is sorted. How can you merge the two subarrays so that `a[0]` to `a[2n-1]` is sorted using an auxiliary array of length `n` (instead of `2n`)?

## 2. Counting inversions.
An inversion in an array `a[]` is a pair of entries `a[i]` and `a[j]` such that `i<j` but `a[i]>a[j]`. Given an array, design a linearithmic algorithm to count the number of inversions.

## 3. Shuffling a linked list.
Given a singly-linked list containing `n` items, rearrange the items uniformly at random. Your algorithm should consume a logarithmic (or constant) amount of extra memory and run in time proportional to `nlogn` in the worst case.

# Hash Tables Interview Questions

## 1. 4-SUM.
Given an array `a[]` of `n` integers, the 4-SUM problem is to determine if there exist distinct indices `i`, `j`, `k`, and `l` such that `a[i]+a[j]=a[k]+a[l]`. Design an algorithm for the 4-SUM problem that takes time proportional to `n**2` (under suitable technical assumptions).

## 2. Hashing with wrong `hashCode()` or `equals()`. 
Suppose that you implement a data type `OlympicAthlete` for use in a `java.util.HashMap`.

* Describe what happens if you override `hashCode()` but not `equals()`.
* Describe what happens if you override `equals()` but not `hashCode()`.
* Describe what happens if you override `hashCode()` but implement `public boolean equals(OlympicAthlete that)` instead of `public boolean equals(Object that)`.

# Elementary Sorts Interview Questions

## 1. Intersection of two sets.
Given two arrays `a[]` and `b[]`, each containing n distinct 2D points in the plane, design a subquadratic algorithm to count the number of points that are contained both in array `a[]` and array `b[]`.

## 2. Permutation.
Given two integer arrays of size `n`, design a subquadratic algorithm to determine whether one is a permutation of the other. That is, do they contain exactly the same entries but, possibly, in a different order.

## 3. Dutch national flag.
Given an array of `n` buckets, each containing a red, white, or blue pebble, sort them by color. The allowed operations are:

* `swap(i,j)`: swap the pebble in bucket `i` with the pebble in bucket `j`.
* `color(i)`: color of pebble in bucket `i`.

The performance requirements are as follows:

* At most `n` calls to `color()`.
* At most `n` calls to `swap()`.
* Constant extra space.

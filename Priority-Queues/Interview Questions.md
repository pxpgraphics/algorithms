# Priority Queues Interview Questions

## 1. Dynamic median.
Design a data type that supports insert in logarithmic time, find-the-median in constant time, and remove-the-median in logarithmic time.

## 2. Randomized priority queue.
Describe how to add the methods `sample()`and `delRandom()` to our binary heap implementation. The two methods return a key that is chosen uniformly at random among the remaining keys, with the latter method also removing that key. The `sample()` method should take constant time; the `delRandom()` method should take logarithmic time. Do not worry about resizing the underlying array.

## 3. Taxicab numbers.
A taxicab number is an integer that can be expressed as the sum of two cubes of integers in two different ways: `a3+b3=c3+d3`. For example, `1729=93+103=13+123`. Design an algorithm to find all taxicab numbers with `a`, `b`, `c`, and `d` less than `n`.

* Version 1: Use time proportional to `n**2logn` and space proportional to `n**2`.
* Version 2: Use time proportional to `n**2logn` and space proportional to `n`.

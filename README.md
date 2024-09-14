# Mediana
Program that determines the median spendings up to the first Sunday (inclusive) of each month using quickselect algorithm, which allows finding the median in linear time (on average), avoiding the need to fully sort the spendings list.

The project contains two main functions:

quickselect(arr, k): A helper function that efficiently finds the k-th smallest element in an array using the Quickselect algorithm.
solution(expenses): An optimized solution that uses Quickselect to compute the median of spendings for each month.


## Introduction
Users specify a map function that processes a key/value pair to generate a set of intermediate key/value pairs, and a reduce function that merges all intermediate values associated with the same intermediate key


## Programming Model
* Map: takes an input pair and produces a set of intermediate key/value pairs
* Reduce: accepts an intermediate key I and a set of values for that key, merges together these values to form a possibly smaller set of values

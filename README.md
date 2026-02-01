Title - Two Sum level easy. The program solves the Two Sum problem by finding two different elements in an integer array whose sum equals a given target value.

It works by scanning the array once from left to right while keeping track of previously seen numbers and their indices using a hash-based data structure. For each element, it computes the value needed to reach the target when added to the current number. If this needed value has already been encountered, the program immediately returns the indices of the two numbers. Because hash lookups are fast, the solution runs efficiently in linear time.

This approach guarantees that only one pass through the array is required, avoids using the same element twice, and correctly returns the indices in any order as soon as the valid pair is found.

# SPOJ Adausort - Adausort

Ada the Ladybug had a lecture about algorithms. She learned that sorting can be done in O(NlogN) time. She also learned concept of stable sort. For those who missed the lecture, it means that as long as there are two equal elements in the array their mutual position won't change after the sort.

Ada wanted to come up with something new, so she proposed unstable sort. It is sort with following property: "As long as there are two equal elements in the array their mutual position will change after the sort".

As Ada has only theoretical knowledge about it, she has asked you to construct such algorithm for her.

Input

The first line of each test-case will contain an integer 1 ≤ N ≤ 105, the length of an array.

The next line will contain N integers 1 ≤ Ai ≤ 105, the elements of the array.

Output

For each test-case, print N numbers, the indexes of each element on which it was in original array. Indexes start with 1.

Example Input

4
1 2 3 4

Example Output

1 2 3 4

Example Input

3
3 2 1

Example Output

3 2 1

Example Input

6
6 6 6 6 6 6

Example Output

6 5 4 3 2 1

Example Input

5
5 5 2 2 3

Example Output

4 3 5 2 1

Example Input

6
1 2 1 2 1 2

Example Output

5 3 1 6 4 2

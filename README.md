# -Smallest-Window-in-a-String-Containing-All-Characters-of-Another-String
Given two strings S and T, find the minimum window substring in S which contains all characters of T (including duplicates). If no such window exists, return an empty string "".
Explanation:
Count Frequencies:

Create a map to store the count of each character in T.
Sliding Window Approach:

Expand right pointer to include characters.
When all characters from T are found, start contracting left.
Update the minimum substring if a shorter one is found.
Time Complexity:

O(N): Since each character is processed at most twice (once while expanding, once while contracting).

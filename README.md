# LeetCode-3.-Longest-Substring-Without-Repeating-Characters
Given a string, find the length of the longest substring without repeating characters.
the basic idea is, keep a hashmap which stores the characters in string as keys and their positions as values, 
and keep two pointers which define the max substring. move the right pointer(i) to scan through the string , 
and meanwhile update the hashmap. If the character is already in the hashmap, 
then move the left pointer(j) to the right of the same character last found. 
Note that the two pointers can only move forward.

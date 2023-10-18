# CodingQuizToday
Mars Exploration Time Complexity: O(n) as an outer for loop iterates through the characters of s 3 at a time and takes (1/3)n time and has if statements each iteration.

Mars Exploration Space Complexity:O(c) as only one variable, charsAlterated is initialized and use during the code

twoStrings:

My thought process was to compare string1 to string2 and check to see if the character at the first position of string1 was contained in string 2. If it was, I would return 'YES" because they would share a common substring. If "NO" I would perform a recursive call on the substring from index 1 to n of string1 and compare it to each character in string 2. I would repeate this process until "YES" was returned or length of string 1 was 0 and therefore no common substrings existed and would then return "NO".

# SortColumns
Sort and delete specified columns

Runtime: 
- The first for loop checks the length of the string (s) --> it loops through the word
- The second for loop goes through the length of the array itself (n) --> it loops through the array

Therefore runtime is equal to the time it takes to loop through all the strings multiplied by the length of the array: n * s 

Runtime = O(n * s)

The base case would be O(s) because we wouldn't go through the array if we know the length of the strings are not equal to one another --> therefore we would only loop through the first for loop and return -1. 

Space Complexity: We have a list of n integer elements and one bool value, so it occupies n + 1 space --> since n is the highest order the space complexity is O(n)  

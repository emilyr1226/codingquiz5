# codingquiz5
Mars Exploration: 
The time complexity of Mars Exploration would be O(n). This is because first we are intializing two variables, which is constant. Then, we have a for-loop looping through our input string, which is linear. Next, we have if-statements that are all constant, and we are doing constant work inside each one (incrementing counter). Thus, the time complexity is linear. The space complexity of this would be O(1). This is because we are not using more memory than the input memory. 

Two Strings: 
Only some of my test cases worked with my code. My intuition was to use a helper function to keep track of an index for the first string and a counter. The counter would increase if there was a matching character in the two input strings, so the first base case was if the counter is greater than 0, "YES" is returned. However, if the counter is never increased and the index goes past the length of the first string, then "NO" would be returned. I then had another condition incrementing the counter if the character in the first and second string are the same. if not, I did a recursive call.

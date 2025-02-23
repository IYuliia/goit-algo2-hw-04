### Task 1. Expanding the Functionality of a Prefix Tree  

Implement two additional methods for the `Trie` class:  

- `count_words_with_suffix(pattern)`: Counts the number of words that end with the given pattern.  
- `has_prefix(prefix)`: Checks whether there are any words with the given prefix.  

### Technical Requirements  

- The `Homework` class must inherit from the base `Trie` class.  
- The methods must handle incorrect input data appropriately.  
- The input parameters for both methods must be strings.  
- The `count_words_with_suffix` method must return an integer.  
- The `has_prefix` method must return a boolean value.


### Task 2. Finding the Longest Common Prefix  

Create a class `LongestCommonWord` that inherits from the `Trie` class and implements the method `find_longest_common_word`, which finds the longest common prefix for all words in the input array of strings.  

### Technical Requirements  

- The `LongestCommonWord` class must inherit from `Trie`.  
- The input parameter of the `find_longest_common_word` method, `strings`, is an array of strings.  
- The `find_longest_common_word` method must return a string representing the longest common prefix.  
- The time complexity must be **O(S)**, where **S** is the total length of all strings.
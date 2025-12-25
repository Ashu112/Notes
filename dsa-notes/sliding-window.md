# Sliding Window 
Used to solve problems of subarray and substring.

# Key Points
- Creates a window or a range
- Computation of next window based on previous result.
  
# Used in
- Subarray with specific sum
- longest substring with unique character
- fixed window size problem.

# How to use Sliding Window
There are two types of sliding window
- Fixed Size 
- Variable Size
  
# Fixed Size Sliding Window
- Find the size of window(k).
- Compute result for first window.
- Loop to compute result of new window by sliding one.
  
# Varaible Size Sliding Window
- Increase the right pointer according to condition.
- if condition does not pass shrink the window from left side.
- Continue this till we reach end of array.

# How to indentify
- Max/Min in subarray or substring
- Size ofsubarry or substring is K 
  
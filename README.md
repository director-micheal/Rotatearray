The rotLeft function is designed to perform d number of left rotations on an array a. The function works as follows:

It first determines the length of the array n.
A new array rotatedArray is created to hold the rotated elements.
A for-loop runs through each index i of the original array.
For each element, it calculates the new index after d rotations using (i + d) % n, which ensures the circular nature of the array.
The element at this new index is then placed into the rotatedArray.
After all elements have been rotated, the rotatedArray is returned

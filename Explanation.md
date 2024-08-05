
The kthDistinct function identifies the k-th distinct string in an array arr. It first counts the occurrences of each string using a dictionary. 
Then, it traverses the array to collect strings that appear exactly once into a list. 
Finally, it checks if there are at least k distinct strings and returns the k-th one (accounting for zero-based indexing). 
If fewer than k distinct strings are found, it returns an empty string. This approach ensures the function efficiently handles the input in linear time.

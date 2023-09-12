# Insertion Sort Project

[22,27,16,2,18,6] -> Insertion Sort

1. Write the stages of the above sequence according to the sort type.
+ [22,27,16,2,18,6] - (n)
+ [2,27,16,22,18,6] - (n-1)
+ [2,6,16,22,18,27] - (n-2)
+ [2,6,16,22,18,27] - (n-3)
+ [2,6,16,18,22,27] - (n-4)

2. Write the Big-O notation. \
n+(n-1)+(n-2)+(n-3)+(n-4)+1 = (n(n+1))/2 = (n^2+n)/2 \
big o = o(n^2)

3. **Time Complexity**: After the array is sorted, which of the following cases does the number 18 fall under? Write

Average case: The number we are looking for is in the middle \
Worst case: The number we are looking for is at the end \
Best case: The number we are looking for is at the beginning of the array.

+ 18 is middle in array. **Average Case** 

### Write the first 4 steps of the sequence [7,3,5,8,2,9,4,15,6] according to Selection Sort.

+ [7,3,5,8,2,9,4,15,6]
+ [2,3,5,8,7,9,4,15,6]
+ [2,3,4,8,7,9,5,15,6]
+ [2,3,4,5,7,9,8,15,6]



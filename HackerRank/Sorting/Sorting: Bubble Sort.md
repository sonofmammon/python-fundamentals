Consider the following version of Bubble Sort:

    for (int i = 0; i < n; i++) {
	    for (int j = 0; j < n - 1; j++) {
	        // Swap adjacent elements if they are in decreasing order
	        if (a[j] > a[j + 1]) {
	            swap(a[j], a[j + 1]);
	        }
	    }
    }

Given an array of integers, sort the array in ascending order using the  _Bubble Sort_  algorithm above. Once sorted, print the following three lines:

1.  `Array is sorted in numSwaps swaps.`, where  is the number of swaps that took place.
2.  `First Element: firstElement`, where  is the  _first_  element in the sorted array.
3.  `Last Element: lastElement`, where  is the  _last_  element in the sorted array.

**Hint:**  To complete this challenge, you must add a variable that keeps a running tally of  _all_  swaps that occur during execution.

For example, given a worst-case but small array to sort:  we go through the following steps:

```
swap    a       
0       [6,4,1]
1       [4,6,1]
2       [4,1,6]
3       [1,4,6]
```

It took  swaps to sort the array. Output would be

    Array is sorted in 3 swaps.  
    First Element: 1  
    Last Element: 6  

**Function Description**
Complete the function  _countSwaps_  in the editor below. It should print the three lines required, then return.
countSwaps has the following parameter(s):

-   _a_: an array of integers .

**Input Format**

The first line contains an integer,  , the size of the array  .  
The second line contains  space-separated integers  .

**Constraints**

**Output Format**

You must print the following three lines of output:

1.  `Array is sorted in numSwaps swaps.`, where  is the number of swaps that took place.
2.  `First Element: firstElement`, where  is the  _first_  element in the sorted array.
3.  `Last Element: lastElement`, where  is the  _last_  element in the sorted array.

**Sample Input 0**

```
3
1 2 3

```

**Sample Output 0**

```
Array is sorted in 0 swaps.
First Element: 1
Last Element: 3

```

**Explanation 0**  
The array is already sorted, so  swaps take place and we print the necessary three lines of output shown above.

**Sample Input 1**

```
3
3 2 1

```

**Sample Output 1**

```
Array is sorted in 3 swaps.
First Element: 1
Last Element: 3

```

**Explanation 1**  
The array is  _not sorted_, and its initial values are:  . The following  swaps take place:

At this point the array is sorted and we print the necessary three lines of output shown above.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3OTc3MDIzMzldfQ==
-->
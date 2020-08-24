# Hash Tables: Ice Cream Parlor

Each time Sunny and Johnny take a trip to the Ice Cream Parlor, they pool their money to buy ice cream. 
On any given day, the parlor offers a line of flavors. Each flavor has a cost associated with it.

Given the value of `money` and the `cost` of each flavor for `t` trips to the Ice Cream Parlor, help Sunny and Johnny choose two  _distinct_  flavors such that they spend their entire pool of money during each visit. ID numbers are the  _1- based_  index number associated with a `cost`. For each trip to the parlor, print the ID numbers for the two types of ice cream that Sunny and Johnny purchase as two space-separated integers on a new line. You must print the smaller ID first and the larger ID second.

For example, there are `n = 5` flavors having `cost = [2,1,3,5,6]`. Together they have `money = 5` to spend. They would purchase flavor ID's `1` and `3` for a cost of `2 + 3 = 5`. Use `1` based indexing for your response.

**Note:**
-   Two ice creams having unique IDs *i* and `j` may have the same cost (i.e., `cost[i] == cost[j]`).
-   There will always be a unique solution.

## **Function Description**

Complete the function  _whatFlavors_  in the editor below. It must determine the two flavors they will purchase and print them as two space-separated integers on a line.

whatFlavors has the following parameter(s):

-   _cost_: an array of integers representing price for a flavor
-   _money_: an integer representing the amount of money they have to spend

**Input Format**

The first line contains an integer, `t`, the number of trips to the ice cream parlor.
Each of the next *t* sets of `3` lines is as follows:
-   The first line contains `money`.
-   The second line contains an integer, `n`, the size of the array `cost`.
-   The third line contains `n` space-separated integers denoting the `cost[i]`.

**Output Format**

Print two space-separated integers denoting the respective indices for the two distinct flavors they choose to purchase in ascending order. Recall that each ice cream flavor has a unique ID number in the inclusive range from `1` to `|cost|`.

**Sample Input**
```
2
4
5
1 4 5 3 2
4
4
2 2 4 3
```
**Sample Output**
```
1 4
1 2
```
**Explanation**
Sunny and Johnny make the following two trips to the parlor:

1.  The first time, they pool together `money = 4` dollars. There are five flavors available that day and flavors `1` and `4` have a total cost of `1 + 3 = 4`.
2.  The second time, they pool together `money = 4` dollars. There are four flavors available that day and flavors `1` and `2` have a total cost of `2 + 2 = 4`.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MTQ5MzA0OTUsLTE1Nzg4OTI0OTddfQ
==
-->
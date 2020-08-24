A string is said to be a  _special string_  if either of two conditions is met:
-   All of the characters are the same, e.g.  `aaa`.
-   All characters except the middle one are the same, e.g.  `aadaa`.

A  _special substring_  is any substring of a string which meets one of those criteria. 
Given a string, determine how many special substrings can be formed from it.
For example, given the string `s = mnonpoo`, we have the following special substrings:  
`{m, n, o, n, o, p, o, o, non, ono, opo, oo}`.

## Function Description
Complete the  _substrCount_  function in the editor below. 
It should return an integer representing the number of special substrings that can be formed from the given string.
*substrCount* has the following parameter(s):
 -   _n_: an integer, the length of string  _s_
 -   _s_: a string

**Input Format**
 - The first line contains an integer, **n**, the length of **s**.   
 - The second line contains the string **s**.
 
**Output Format**
 - Print a single line containing the count of total special substrings.

**Sample Input 0**

    5
    asasd

**Sample Output 0**

    7 

**Explanation 0**
The special palindromic substrings of `s = asasd` are `{a, s, a, s, d, asa, sas}`

**Sample Input 1**

    7
    abcbaba
**Sample Output 1**

    10 

**Explanation 1**
The special palindromic substrings of `s = abcbaba` are `{a, b, c, b, a, b, a, bcb, bab, aba}`

**Sample Input 2**

    4
    aaaa
**Sample Output 2**

    10

**Explanation 2**
The special palindromic substrings of `s = ab` are `{a, b, c, b, a, b, a, bcb, bab, aba}`

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMDA4NDY1MzMsLTY1NzI4MzQ4NywxOT
g1NjQ0ODc5XX0=
-->
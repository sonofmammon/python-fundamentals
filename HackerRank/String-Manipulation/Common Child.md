A string is said to be a child of a another string if it can be formed by deleting 0 or more characters from the other string. Given two strings of equal length, what's the longest string that can be constructed such that it is a child of both?

For example,  `ABCD`  and  `ABDC`  have two children with maximum length 3,  `ABC`  and  `ABD`. They can be formed by eliminating either the  `D`  or  `C`  from both strings. Note that we will not consider  `ABCD`  as a common child because we can't rearrange characters and  `ABCD` != `ABDC`.

## Function Description
Complete the  _commonChild_  function in the editor below. 
It should return the longest string which is a common child of the input strings.

*commonChild* has the following parameter(s):
-   _s1, s2_: two equal length strings

### **Input Format**

 - There is one line with two space-separated strings, `s1` and `s2`.

### **Output Format**

 - Print the length of the longest string `s`, such that `s` is a child of both `s1` and `s2`.

**Sample Input**
```
HARRY
SALLY
```
**Sample Output**
```
 2
```
**Explanation**
The longest string that can be formed by deleting zero or more characters from `HARRY` and `SALLY` is `AY`, whose length is 2.

## SAMPLE 1
**Sample Input 1**
```
AA
BB
```
**Sample Output 1**
```
0
```
**Explanation 1**
`AA`and `BB` have no characters in common and hence the output is 0.

## SAMPLE 2
**Sample Input 2**
```
SHINCHAN
NOHARAAA
```
**Sample Output 2**
```
3
```
**Explanation 2**
The longest string that can be formed between `SHINCHAN` and `NOHARAAA` while maintaining the order is `NHA`.

## SAMPLE 3
**Sample Input 3**
```
ABCDEF
FBDAMN
```
**Sample Output 3**
```
2
```
**Explanation 3**  
`BD` is the longest child of the given strings.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI0NDkxMTI3NV19
-->
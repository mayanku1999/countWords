# countWords
Input Format:
1) First line contain only single Integer denoting the size of dictionary (say N).
2) Next N line contain words from  Dictionary.
3) In next line enter the string in which you want to search your dictionary words.

Output Format:
1) First N line contains dictionary word and space separated, its occurence(either original form or scrambled form) in string.
2) Final answer that sum of all occurence of all dictionary word in string.





Deepti loves cruises. she is going to visit the Carribean on a Cruise. So, she thought of providing everyone who is traveling with her with lunch as well. Each food item is denoted by an integer ID. A lunchbox contains exactly **A** food items. she has a list of food items with her denoted by an integer array **B**. she asked you to tell her the maximum number of lunchboxes she can prepare. 
**Note:** A lunch box can contain multiple same kinds of food items but the content of each lunch box should be the same.

**Problem Const:**
1<=A<=|B|<=10^5
1<=B[i]<=10^5

**Input:**
First line contain integer A
Second line cntain array B

**Output:**
Return a single integer denoting the maximum number of lunch boxes that can be prepared.

**Example Input:**
**Input 1:**
A=4, B=[1,2,3,2,6,1,3]
**Input 2:**
A=4, B=[1,3,1,3,10,3,6,6,13]
**Input 3:**
A=4 B=[1,3,3,3,3,6,6,10,13]

**Example Output:**
**output 1:**
2
**Output 2:**
1
**Output 3:**
2

**Example explanation:**
**Explanation 1:**
she can prepare content to be [1,2,3] and prepare 2 lunchboxes.
**Explanation 2:**
she can choose content to be [1,3,3,3]
**Explanation 3:**
she can choose content [1,3,3,6] and prepare 2 lunchboxes.

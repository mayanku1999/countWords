# countWords
Input Format:
1) First line contain only single Integer denoting the size of dictionary (say N).
2) Next N line contain words from  Dictionary.
3) In next line enter the string in which you want to search your dictionary words.

Output Format:
1) First N line contains dictionary word and space separated, its occurence(either original form or scrambled form) in string.
2) Final answer that sum of all occurence of all dictionary word in string.

<br/><br/><br/>



Deepti loves cruises. she is going to visit the Carribean on a Cruise. So, she thought of providing everyone who is traveling with her with lunch as well. Each food item is denoted by an integer ID. A lunchbox contains exactly **A** food items. she has a list of food items with her denoted by an integer array **B**. she asked you to tell her the maximum number of lunchboxes she can prepare. <br/>
**Note:** A lunch box can contain multiple same kinds of food items but the content of each lunch box should be the same.<br/><br/>

**Problem Const:**<br/>
1<=A<=|B|<=10^5<br/>
1<=B[i]<=10^5
<br/><br/>
**Input:**
First line contain integer A<br/>
Second line cntain array B
<br/><br/>
**Output:**
Return a single integer denoting the maximum number of lunch boxes that can be prepared.
<br/><br/>
**Example Input:**<br/>
**Input 1:**<br/>
A=3, B=[1,2,3,2,6,1,3]<br/>
**Input 2:**<br/>
A=4, B=[1,3,1,3,10,3,6,6,13]<br/>
**Input 3:**<br/>
A=4 B=[1,3,3,3,3,6,6,10,13]<br/>
<br/>
**Example Output:**<br/>
**output 1:**<br/>
2<br/>
**Output 2:**<br/>
1<br/>
**Output 3:**<br/>
2<br/><br/>

**Example explanation:**<br/>
**Explanation 1:**<br/>
she can prepare content to be [1,2,3] and prepare 2 lunchboxes.<br/>
**Explanation 2:**<br/>
she can choose content to be [1,3,3,3]<br/>
**Explanation 3:**<br/>
she can choose content [1,3,3,6] and prepare 2 lunchboxes.<br/>

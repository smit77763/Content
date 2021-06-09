# <font size =7> Arrays </font>


<font size =3>

> ##   What is Array?




  * An **`array`** is a collection of items stored at contiguous memory locations.

 
*  In Arrays multiple items of same type can be stored together which makes it  easier to calculate the position of each element by simply adding an offset to a base value.

<img src = "data:image/png;base64,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">



>## Defining An Array


*  The size of the array is `fixed` and the memory for an array needs to be allocated before use, `the size of an array cannot be increased or decreased dynamically.`



>	##  General Declaration
```
	dataType arrayName[arraySize];
```


> ## Accessing array elements 
* Indexing of an array starts from 0 to n-1;
* Element present at ith index in the array arr[] can be accessed as arr[i].</font>
</br>
<img src="data:image/png;base64,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">



> ## Operations:-


<details open> <summary><font size =5>1. Searching</font></summary>

* We can use loops to perform the above operation of array traversal and access the elements, using indexes
</br>
</br>
	
    > Eg :-. For searching the element stored in key in array of size n
    

  </br>
<font size =3>

> **Example Code**
``` 

       int a[n]; // Array Declaration
        //Traversing An Array Through Loop
	
		for(i=0 ;i<n;i++) {  
              
		if(arr[i]==key) {   
		
		print "ELEMENT FOUND";
		
		}
	
		else{
		print "ELEMENT NOT FOUND";
		}	}


  ``` 
 Hello

 <br>   
</font>



 > **Time Complexity** : - 
>####   **O(n)** - as worst Case if required element is at last index
>#### **O(1)**  -  as best case if required element is at first position



   </details>


 <details> <summary><font size =5> 2. Insertion</font></summary>
 

**1.Insert elements at the end of the array.**

* Suppose there is an array ‘arr’  of size ‘N’ and length of an array is  ‘len’.
* To insert  an element k at the end of the arr[]
 The first step is to check if there is any space left in the array for new element. 
```
if(len < N)
     // space left
else
     // array is full
```
* If there is space left for the new element, insert it directly at the end at position len + 1 and index len:
```
arr[len] = k;
```

>**Time Complexity :-**
>
> <b>O(1)</b> as we are directly inserting the element in a single operation.

</br>

**2. Insert element at any given index in the array.**

* Suppose we have to insert element ‘k’ at index ‘idx’.
* For this opearation we have to check  if there is any space left in the array for new element. 

* To do this check following ,
```
if(len < N)
     // space left
else
     // array is full
```

* Now, if there is space left, the element can be inserted. The index of the new element will be idx = pos - 1.
* Before inserting the elements at idx shift all elements from the index idx till end of the array to the right by 1 place.
>**Implementation**
```
for(i = len-1; i >= idx; i--)
{
    arr[i+1] = arr[i];
}
```
*  After Shifting the elements place k at index idx.
arr[idx] = K;

><b>Time Complexity : - </b>
>
> <b>O(N) </b>as in worst case we might  have to shift all of the elements by one place to the right.


</details>

<details><summary><font size =5>3.Deletion</font></summary> </summary>


* To delete a given element from an array, we will have to first search the element in the array.
* If the element is present in the array then delete operation is performed for the element otherwise the user is notified that the array does not contains the given element.
* For Deleting an element K from the array arr[] , Search the element K in the array arr[] to find the index at which it is present.

</br>

```
for(i = 0; i < N; i++){
    if(arr[i] == K)
        idx = i; return;
    else
        Element not Found;
}
```

*	Now, to delete the element present at index idx, left shift all of the elements present after idx by one place and finally reduce the length of the array by 1. 

```
for(i = idx+1; i < len; i++)
{
    arr[i-1] = arr[i];
}
len = len-1;

```

>**Time Complexity : -**
>
> <b>O(N) </b> in worst case as we might have to shift all of the elements by one place to the left.

</details>



<details><summary><font size =5>4. Array Rotation</font></summary>

* Consider the following array  :- 

<img src="https://media.geeksforgeeks.org/wp-content/uploads/simplearray.png">
 

* The above array is rotated `counter-clockwise`(towards left) by 2 elements.

<img src ="https://media.geeksforgeeks.org/wp-content/uploads/arrayRotation.png">
* After rotation, the array will be:
 
<b>	The process looks like following :-</b>

1.	Shift all elements after K-th element to the left by K positions.
6.	Fill the K blank spaces at the end of the array by first K elements from the original array.

` The similar approach can also be applied for clockwise array rotation.`

> ### 	**Implementations**

### **a)	Simple Method**
1.	Store the first K elements in a temporary array say temp[].
2.	Shift all elements after K-th element to the left by K positions in the original array.
3.	Fill the K blank spaces at the end of the original array by the K elements from the temp array.

>**Algorithm**
>
>Say, `arr[]` = [1, 2, 3, 4, 5, 6, 7] ,` K` = 2
>1) Store first K elements in a temp array
   temp[] = [1, 2]
>2) Shift rest of the arr[]
   arr[] = [3, 4, 5, 6, 7, 6, 7]
>3) Store back the K elements from temp
   arr[] = [3, 4, 5, 6, 7, 1, 2]


> **Time Complexity : -  O(N)** as we have to shift all N elements.

> **Auxiliary Space : -  O(K)** where k is the number of places by which elements will be rotated.

### **b)	 Another Method (Without Extra Space)**  
*	We can also rotate an array by avoiding the use of temporary array.
* The idea is to rotate the array one by one `K times.`
>**Algorithm**
>
>1.	Store the first element in a temporary variable say temp.
>2.	Left shift all elements after the first element by 1 position. That is, move arr[1] to arr[0], arr[2] to arr[1] and so on.
>3.	Initialize arr[N-1] with temp.

* To rotate an array by K position to the left, repeat the above process K times.

>Eg :-
>
>arr[] = [1, 2, 3, 4, 5, 6, 7], K = 2
>
>Rotate arr[] one by one 2 times.
>
>After 1st rotation: [2, 3, 4, 5, 6, 7, 1]
> After 2nd rotation: [ 3, 4, 5, 6, 7, 1, 2]


>**Time Complexity  :-  O(N*K)** where` N` is the number of elements in the array and `K `is the number of places by which elements will be rotated.

>**Auxiliary Space : -  O(1)** as one storage space is used.

### **c)	Juggling Algorithm : -**

*	Here , Instead of moving one by one , `divide the array in different sets where number of sets is equal to GCD of N and K and move the elements within sets.`

*	`If GCD is 1` as is for the above example array (N = 7 and K = 2), then elements will be moved within one set only, we just start with temp = arr[0] and keep moving arr[I+d] to arr[I] and finally store temp at the right place.
>
>**Example :-**
>

```

Here is an example for N = 12 and K = 3. GCD of N and K is 3.

Let arr[] be {1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12}

a) Elements are first moved in first set – (See below  diagram for this movement)

 arr[] after this step --> {4 2 3 7 5 6 10 8 9 1 11 12}

b) Then in second set.

       arr[] after this step --> {4 5 3 7 8 6 10 11 9 1 2 12}

c) Finally in third set.

       arr[] after this step --> {4 5 6 7 8 9 10 11 12 1 2 3}
```

<img src ="https://media.geeksforgeeks.org/wp-content/uploads/20201105102721/jugglearray-300x113.png">

>**Time Complexity:-  O(N)**, as worst case because we have shift all elements of the array.

>**Auxiliary Space:-  O(1)** , here as one temporary variable is needed.

</details>

<details><summary><font  size=5 >5. Reversing An Array </font></summary>

* Reversing an array means reversing the order of the elements in the given array.

*	Suppose you have to reverse the following array : -

### **Iterative Solution**

### **1.	Using Temporary Array : -**

*  The idea is to first copy all of the elements of the given array in a temporary array.
* Then traverse the temporary array from end and replace elements in original array by elements of temp array.

>**Auxiliary Space : - O(N)**

### **2.	Efficient One :-**
-	The idea is to `traverse the array from both ends and keep swapping elements from both ends until middle of the array is reached`.
>**Algorithm**
```
1) Initialize start and end indexes as 
   start = 0, end = N-1
2) In a loop, swap arr[start] with arr[end] 
   and change start and end as follows :
       start = start + 1, 
       end = end – 1
```
For Reference : -
<img src="https://media.geeksforgeeks.org/wp-content/uploads/arra34.jpg">
 

>**Time Complexity : -  O(N)** , as we have to change all the elements.
 
### **Recursive Solution**
> **Algorithm**
```
1) Initialize start and end indexes as 
   start = 0, end = n-1
2) Swap arr[start] with arr[end]
3) Recursively call reverse for rest of the array.

```




>**Recursive Function : -**
```
void reverseArray(arr[], start, end) 
{ 
    if (start >= end) 
        return; 
    
    // Swap elements at start and end  
    temp = arr[start];  
    arr[start] = arr[end];
    arr[end] = temp; 
      
    // Recursive Function calling 
    reverseArray(arr, start + 1, end - 1);  
}   
```

>**Time Complexity : -  O(N)** ,  as we have to shift all elements .

</details>



</br>


> ## Important Concepts
 
<details open><summary><font size =5>1.Sliding Window Technique</font> </summary>

* This technique `shows how a nested ‘for loop’ in few problems can be converted to a single ‘for loop; and hence reducing time complexity.
`
>**Example**

```
Q. Given an array of integers of size 'n'. Our aim is to calculate the maximum sum of 'k' consecutive elements in the array.

Input  : arr[] = {100, 200, 300, 400}
         k = 2
Output : 700
```
### **Naïve Approach  : -**
*	We have to find the sum of each k consecutive elements and compare which block has the maximum sum possible .

>**Time Complexity : -  O(n*k)**

### **Sliding Window Technique**
* To understand this topic lets take an example of window pane in bus .
* Consider of window of length n and the pane which is fixed in it of length  k;
*	Initially the pane is at extreme left i.e., at 0 units from the left. 
*	Now, co-relate the window with array arr[] of size n and plane with current_sum of size k elements. 
* Now, if we apply force on the window such that it moves a unit distance ahead. 
*	The pane will cover next k consecutive elements.
*	Consider an array `arr[] = {5 , 2 , -1 , 0 , 3} and value of k = 3 and n = 5.`

>**Applying sliding window technique : -**

```
1.	We compute the sum of first k elements out of  n terms using a linear loop and store the sum in variable window_sum.

2.	Then we will graze linearly over the array till it reaches the end and simultaneously keep track of maximum sum.

3.	To get the current sum of block of k elements just subtract the first element from the previous block and add the last element of the current block .
```
* This is the initial phase where we have calculated the initial window sum starting from index 0 . At this stage the window sum is 6. Now, we set the maximum_sum as current_window i.e 6.
 
<img src="https://media.geeksforgeeks.org/wp-content/uploads/sliding-window2.png">

* Now, we slide our window by a unit index. Therefore, now it discards 5 from the window and adds 0 to the window. Hence, we will get our new window sum by subtracting 5 and then adding 0 to it. So, our window sum now becomes 1.
*  Now, we will compare this window sum with the maximum_sum. As it is smaller we wont the change the maximum_sum.
 
<img src="https://media.geeksforgeeks.org/wp-content/uploads/sliding-window2.png">


* Similarly, now once again we slide our window by a unit index and obtain the new window sum to be 2. Again we check if this current window sum is greater than the maximum_sum till now. Once, again it is smaller so we don't change the maximum_sum.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/sliding-window3.png">


`Therefore, for the above array our maximum_sum is 6.`

>**Example Code**
 ```
#include <iostream>
using namespace std;
 


// Returns maximum sum in a subarray of size k.
int maxSum(int arr[], int n, int k)
{
    // n must be greater
    if (n < k) {
        cout << "Invalid";
        return -1;
    }
     
    // Compute sum of first window of size k
    int max_sum = 0;
    for (int i = 0; i < k; i++)
        max_sum += arr[i];
 
    // Compute sums of remaining windows by
    // removing first element of previous
    // window and adding last element of
    // current window.
    int window_sum = max_sum;
    for (int i = k; i < n; i++) {
        window_sum += arr[i] - arr[i - k];
        max_sum = max(max_sum, window_sum);
    }
 
    return max_sum;
}
 
// Driver code
int main()
{
    int arr[] = { 1, 4, 2, 10, 2, 3, 1, 0, 20 };
    int k = 4;
    int n = sizeof(arr) / sizeof(arr[0]);
    cout << maxSum(arr, n, k);
    return 0;
}

```

>**Time Complexity : - O(n)**

</details>

<details><summary><font size =5>2. Prefix Sum Array</font></summary>

*  The prefix sum array of any array, arr[] is defined as an array of same size say,` prefixSum[] such that the value at any index i in prefixSum[] is sum of all elements from indexes 0 to i in arr[].`

>**Example**
```
Input  : arr[] = {10, 20, 10, 5, 15}
Output : prefixSum[] = {10, 30, 40, 45, 60}
```
>**Explanation :** 
```
While traversing the array, update 
the element by adding it with its previous element.
prefixSum[0] = 10, 
prefixSum[1] = prefixSum[0] + arr[1] = 30, 
prefixSum[2] = prefixSum[1] + arr[2] = 40 and so on.
```

> **Function To generate prefix sum array :-**
```
void fillPrefixSum(int arr[], int N, int prefixSum[]) 
{ 
    prefixSum[0] = arr[0]; 
  
    // Adding present element  
    // with previous element 
    for (int i = 1; i < N; i++) 
        prefixSum[i] = prefixSum[i-1] + arr[i]; 
}
```
### **Finding Sum in Range : -**

* Since the array prefixSum[i] stores the sum of all elements upto i. 
* Therefore, prefixSum[j] - prefixSum[i] will give:
```
sum of elements upto j-th index - sum of elements upto i-th element   
```
```
sumInRange = prefixSum[j]  , if i = 0
otherwise,
sumInRange = prefixSum[j] - prefixSum[i-1]  ,  if (i != 0)
```

</details>

</br>

</br>

> ## **Interview Coding Problems**



<details open><summary><font size =5> 1.Beginner Level</font></summary>
</br>

<details><summary><font size =4>1.Check if a key is present in every segment of size k in an array</font></summary>

* **Given an array arr[] and size of array is n and one another key x, and give you a segment size k. The task is to find that the key x present in every segment of size k in arr[].**

> Example 
```
Input : 
arr[] = { 3, 5, 2, 4, 9, 3, 1, 7, 3, 11, 12, 3} 
x = 3 
k = 3 
Output : Yes 
There are 4 non-overlapping segments of size k in the array, {3, 5, 2}, {4, 9, 3}, {1, 7, 3} and {11, 12, 3}. 3 is present all segments.
I

```
* [Solution](https://www.geeksforgeeks.org/check-if-a-key-is-present-in-every-segment-of-size-k-in-an-array/)
</details>

<details><summary><font size =4>2.Find the frequency of a number in an array.</font></summary>

* **Given an array, a[], and an element x, find a number of occurrences of x in a[]**.

> Example

 ```

Input  : a[] = {0, 5, 5, 5, 4}
           x = 5
Output : 3

Input  : a[] = {1, 2, 3}
          x = 4
Output : 0

```

* [Solution](https://www.geeksforgeeks.org/find-frequency-number-array/)

</details>

<details><summary><font size =4>3.Range and Coefficient of range of Array</font></summary>

* **Given an array arr of integer elements, the task is to find the range and coefficient of range of the given array where:
Range: Difference between the maximum value and the minimum value in the distribution. 
Coefficient of Range: (Max – Min) / (Max + Min)**


> Example
 
```
Input: arr[] = {15, 16, 10, 9, 6, 7, 17} 
Output: Range : 11 
Coefficient of Range : 0.478261 
Max = 17, Min = 6 
Range = Max – Min = 17 – 6 = 11 
Coefficient of Range = (Max – Min) / (Max + Min) = 11 / 23 = 0.478261
Input: arr[] = {5, 10, 15} 
Output: Range : 10 
Coefficient of Range : 0.5 

```

* [Solution](https://www.geeksforgeeks.org/range-and-coefficient-of-range-of-array/)

</details>
<details><summary><font size=4>4.Sort an array of 0s, 1s and 2s</font></summary>

* **Given an array A[] consisting 0s, 1s and 2s. The task is to write a function that sorts the given array. The functions should put all 0s first, then all 1s and all 2s in last.** 

> Examples

```
Input: {0, 1, 2, 0, 1, 2}
Output: {0, 0, 1, 1, 2, 2}

Input: {0, 1, 1, 0, 1, 2, 1, 2, 0, 0, 0, 1}
Output: {0, 0, 0, 0, 0, 1, 1, 1, 1, 1, 2, 2}


```
* [Solution](https://www.geeksforgeeks.org/sort-an-array-of-0s-1s-and-2s/)

</details>

<details><summary><font size=4>5.Union and Intersection of two sorted arrays</font></summary>

* **Given two sorted arrays, find their union and intersection**

>Example

```
Input : arr1[] = {1, 3, 4, 5, 7}
        arr2[] = {2, 3, 5, 6} 
Output : Union : {1, 2, 3, 4, 5, 6, 7} 
         Intersection : {3, 5}

Input : arr1[] = {2, 5, 6}
        arr2[] = {4, 6, 8, 10} 
Output : Union : {2, 4, 5, 6, 8, 10} 
         Intersection : {6}

```

* [Solution](https://www.geeksforgeeks.org/union-and-intersection-of-two-sorted-arrays-2/)

</details>

</details>

</br>




<details><summary><font size =5>2.Intermidiate Level</font></summary>

</br>

<details><summary><font size =4>1.Program to cyclically rotate an array by one</font></summary>

* **Given an array, cyclically rotate the array clockwise by one.**

>Example

```dotnetcli

Input:  arr[] = {1, 2, 3, 4, 5}

Output: arr[] = {5, 1, 2, 3, 4}

```

* [Solution](https://www.geeksforgeeks.org/c-program-cyclically-rotate-array-one/)
</details>

<details><summary><font size =4>2.Minimum number of jumps </font></summary>

* **Given an array of N integers arr[] where each element represents the max number of steps that can be made forward from that element. Find the minimum number of jumps to reach the end of the array (starting from the first element). If an element is 0, then you cannot move through that element.**

>Example:

```dotnetcli
Input:
N = 11 
arr[] = {1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9} 
Output: 3 
Explanation: 
First jump from 1st element to 2nd 
element with value 3. Now, from here 
we jump to 5th element with value 9, 
and from here we will jump to last.

```

**Task : -**

>You don't need to read input or print anything. Your task is to complete function minJumps() which takes the array arr and it's size N as input parameters and returns the minimum number of jumps.

**Expected Time
Complexity:** *O(N)*

**Expected Space Complexity:** *O(1)*

**Constraints:**

</br>

```
1 ≤ N ≤ 107

0 ≤ ai ≤ 107
```



* [Solution]()

</details>

<details><summary><font size =4>3.Factorials of large numbers.</font></summary>

* **Given an integer N, find its factorial.**

>Example

```dotnetcli
Input: N = 10
Output: 3628800

Explanation :
10! = 1*2*3*4*5*6*7*8*9*10 = 3628800


```

* **Expected Time Complexity :** *O(N)*

* **Expected Auxilliary Space :** *O(1)*

 

* **Constraints:**
1 ≤ N ≤ 1000

* [Solution](https://practice.geeksforgeeks.org/problems/factorials-of-large-numbers2508/1)

</details>

<details><summary><font size =4>4.Longest consecutive subsequence.</font></summary>

* **Given an array of positive integers.** 

* **Find the length of the longest sub-sequence such that elements in the subsequence are consecutive integers, the consecutive numbers can be in any order.**

> Example

```dotnetcli
Input:
N = 7
a[] = {1,9,3,10,4,20,2}
Output: 4

Explanation:
1, 2, 3, 4 is the longest
consecutive subsequence.

```

* **Expected Time Complexity:** *O(N).*

* **Expected Auxiliary Space:** *O(N).*


* **Constraints:**

```
1 <= N <= 105

0 <= a[i] <= 105
```

* [Solution](https://practice.geeksforgeeks.org/problems/longest-consecutive-subsequence2449/1)


</details>

<details><summary><font size =4>5.Sort an array in wave form</font></summary>

* **Given an unsorted array of integers, sort the array into a wave like array.** 

* **An array ‘arr[0..n-1]’ is sorted in wave form if arr[0] >= arr[1] <= arr[2] >= arr[3] <= arr[4] >= …..**

>Example

```dotnetcli

Input:  arr[] = {10, 5, 6, 3, 2, 20, 100, 80}
 Output: arr[] = {10, 5, 6, 2, 20, 3, 100, 80} OR
                 {20, 5, 10, 2, 80, 6, 100, 3} OR
                 any other array that is in wave form

 
Input:  arr[] = {20, 10, 8, 6, 4, 2}
 Output: arr[] = {20, 8, 10, 4, 6, 2} OR
                 {10, 8, 20, 2, 6, 4} OR
                 any other array that is in wave form

```

* [Solution](https://www.geeksforgeeks.org/sort-array-wave-form-2/)

</details>

</details>
</br>



<details><summary><font size =5> 3.Advanced Level</font></summary>


<details><summary><font size =4>1.Trapping Rain Water</font></summary>

* **Given n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it is able to trap after raining.**

>Example

```dotnetcli
Input: arr[]   = {2, 0, 2}
Output: 2

```

* [Solution](https://www.geeksforgeeks.org/trapping-rain-water/)

</details>


<details><summary><font size =4>2.Chocolate Distribution Problem </font></summary>

* **Given an array A[ ] of positive integers of size N, where each value represents the number of chocolates in a packet.** 

* **Each packet can have a variable number of chocolates. There are M students, the task is to distribute chocolate packets among M students such that :**

1. Each student gets exactly one packet.
2. The difference between maximum number of chocolates given to a student and minimum number of chocolates given to a student is minimum.

> Example

```dotnetcli
Input:
N = 7, M = 3
A = {7, 3, 2, 4, 9, 12, 56}

Output: 2

Explanation: 
The minimum difference between
maximum chocolates and minimum chocolates
is 4 - 2 = 2 by choosing following M packets :
{3, 2, 4}.

```
* **Expected Time Complexity:** *O(N*Log(N))*

* **Expected Auxiliary Space:** *O(1)*

* **Constraints:**

```
1 ≤ T ≤ 100
1 ≤ N ≤ 105
1 ≤ Ai ≤ 109
1 ≤ M ≤ N

```

* [Solution](https://practice.geeksforgeeks.org/problems/chocolate-distribution-problem3825/1)

</details>

<details><summary><font size =4>3.Find the median</font></summary>

* **Given an array arr[] of N integers, calculate the median.**
>Example 

```dotnetcli

Input: N = 4
arr[] = 56 67 30 79â€‹

Output: 61
Explanation: In case of even number of 
elemebts average of two middle elements 
is the median.

```
* **Expected Time Complexity:** *O(n * log(n))*

* **Expected Space Complexity:** *O(1)*
 

* **Constraints:**

```
1 <= Length of Array <= 100
1 <= Elements of Array <= 100
```

* [Solution](https://practice.geeksforgeeks.org/problems/find-the-median0527/1)

</details>

<details><summary><font size =4>4.Longest Alternating subsequence</font></summary>

* A sequence {x1, x2, .. xn} is alternating sequence if its elements satisfy one of the following relations :

 
```
  x1 < x2 > x3 < x4 > x5 < …. xn or 
  x1 > x2 < x3 > x4 < x5 > …. xn

```
> Example

```dotnetcli
Input: arr[] = {1, 5, 4}
Output: 3
The whole arrays is of the form  x1 < x2 > x3 


Input: arr[] = {1, 4, 5}
Output: 2
All subsequences of length 2 are either of the form 
x1 < x2; or x1 > x2


Input: arr[] = {10, 22, 9, 33, 49, 50, 31, 60}
Output: 6
The subsequences {10, 22, 9, 33, 31, 60} or
{10, 22, 9, 49, 31, 60} or {10, 22, 9, 50, 31, 60}
are longest subsequence of length 6.

```

* [Solution](https://www.geeksforgeeks.org/longest-alternating-subsequence/)

</details>

<details><summary><font size =4>5.Stock Buy Sell to Maximize Profit</font></summary>

* **The cost of a stock on each day is given in an array, find the max profit that you can make by buying and selling in those days.** 
* **For example, if the given array is {100, 180, 260, 310, 40, 535, 695}, the maximum profit can earned by buying on day 0, selling on day 3. Again buy on day 4 and sell on day 6.** 
* **If the given array of prices is sorted in decreasing order, then profit cannot be earned at all.**

* [Solution](https://www.geeksforgeeks.org/stock-buy-sell/)

</details>

</details>


</br>


> ## Questions Asked In Interview 


<details><summary><font size =4>Advantages and Disadvantages of Array? </font></summary>

**Advantages : -**
* We can put in place other data structures like stacks, queues, linked lists, trees, graphs, etc. in Array.

* Arrays can sort multiple elements at a time.
* We can access an element of Array by using an index.



 **Disadvantages : -**

* We have to declare Size of an array in advance. However, we may not know what size we need at the time of array declaration.

* The array is static structure. It means array size is always fixed, so we cannot increase or decrease memory allocation.
<hr>

* The key benefit of an array data structure is that it offers fast **O(1)** search if you know the index, but **adding and removing**an element from an array is slow because**you cannot change the size of the array once it’s created.**
</details>


<details><summary><font size =4> Can we use Generics with the array?</font></summary>

* **No, we cannot use Generic with an array.**

</details>

<details><summary><font size =4>  Where is the memory allocated for arrays in Java?</font></summary>

* In Java, memory for arrays is always allocated on the **heap** as arrays in Java are objects.
</details>

<details><summary><font size =4>What is the difference between array_name and &array_name? </font></summary>

* To understand this question let’s take an example, suppose arr is an integer array of 5 elements.

 > int arr[5];

 * If you print arr and &arr then you found the same result but both have different types.




|arr  |& arr  |
|---------|---------|
|arr=> The name of the array is a pointer to its first element. So here arr split as the pointer to the integer.|&arr=> It split into the pointer to an array that means &arr will be similar to int(*)[5];|
    


</details>

<details><summary><font size =4> What are the advantages of using an array of pointers to string instead of an array of strings? </font></summary>

* An array of pointers to string is useful when sorting the strings, we need to **swap only pointers instead of swapping the whole string** which helps in the efficient use of memory and time.

</details>

<details><summary><font size =4>What is a flexible array in C? </font></summary>

* A very good feature that is introduced by C99 is a flexible array member. 

* This feature enables the user to create an empty array in a structure, the size of the empty array can be changed at runtime as per the user requirements. 

* This empty array should be declared as the last member of the structure and the structure must contain at least one more named member.

**Rules For Creating Flexible Array : -**

* The flexible array member must be the last member of the structure.

* There must be at least one other member.

* The flexible array is declared like an ordinary array, except that the brackets are empty.

> Example

```dotnetcli
struct userData
{
    int iTrackNumber;
  
    float fAmount;
  
  //flexible array member
    char acAddress[];
};
```
</details>
<details><summary><font size =4>Can we create an array of a void type?</font>
</summary>

* **NO**
</details>

</font>

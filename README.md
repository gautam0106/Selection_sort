# Selection_sort
Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted portion. This process is repeated for the remaining unsorted portion of the list until the entire list is sorted.

Algorithm of Selection Sort in C
Make a variable (say min_index) and initialize it to the location 0 of the array.

Traverse the whole array to find the smallest element in the array.

While traversing the array, if we find an element that is smaller than min_index then swap both these elements.

After which, increase the min_index by 1 so that it points to the next element of the array.

Repeat the above process until the whole array is sorted.

Example of Selection Sort in C
Let us take an example of how the selection sort algorithm actually works.

Let's take an array arr that has the following elements.

arr = {4,7,5,3,2,1}

-In the first pass of the array -

First of all, set the variable min_index=0 and then find the smallest element of the array which will be 1 in this case. Therefore, we will swap 1 with arr[min_index]

Now, the array becomes arr = {1,7,5,3,2,4}

-In the second pass of the array -

We increment the min_index by 1 therefore min_index = 1. Now we will find the highest element for the rest of the array which comes out to be 2. Therefore, we will swap 2 with arr[min_index].

Now, the array becomes arr = {1,2,5,3,7,4}

-In the third pass of the array -

The value of min_index = 2 and the highest element in the rest of the array comes out to be 3. Therefore we will swap 3 with arr[min_index]

Now, the array becomes arr = {1,2,3,5,7,4}

-In the fourth pass of the array -

The value of min_index = 3 and the highest element in the rest of the array comes out to be 4. Therefore we will swap 4 with arr[min_index]

Now, the array becomes arr = {1,2,3,4,7,5}

-In the fifth pass of the array -

The value of min_index = 4 and the highest element in the rest of the array comes out to be 5. Therefore we will swap 5 with arr[min_index]

Now, the array becomes arr = {1,2,3,4,5,7}

# Output
<img width="676" alt="image" src="https://user-images.githubusercontent.com/113123292/234486704-9bd015bb-c136-482f-add7-5f9c2569008f.png">

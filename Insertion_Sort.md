


# Insertion  Sort Project

## Insertion Sort Steps

>Array={22,27,16,2,18,6}

- Is 27 < 22 ?  Array=[22,27,16,2,18,6]
- Is 16 < 22 ?  Array=[16,27,22,2,18,6]

- Is 27 < 16 ?  Array=[16,27,22,2,18,6]
- Is 22 < 16 ?  Array=[16,27,22,2,18,6]
- Is 2 < 16 ?   Array=[2,27,22,16,18,6]

- Is 16 < 2 ?   Array=[2,27,22,16,18,6]
- Is 27 < 2 ?   Array=[2,27,22,16,18,6]
- Is 22 < 2 ?   Array=[2,27,22,16,18,6]
- Is 16 < 2 ?   Array=[2,27,22,16,18,6]
- Is 18 < 2 ?   Array=[2,27,22,16,18,6]

- Is 22 < 27 ?  Array=[2,22,27,16,18,6]

- Is 27 < 22 ?  Array=[2,22,27,16,18,6]
- Is 16 < 22 ?  Array=[2,16,27,22,18,6]

- Is 27 < 16 ?  Array=[2,16,27,22,18,6]
- Is 22 < 16 ?  Array=[2,16,27,22,18,6]
- Is 18 < 16 ?  Array=[2,16,27,22,18,6]
- Is 6 < 16 ?   Array=[2,6,27,22,18,16]

- Is 6 < 27 ?   Array=[2,6,27,22,18,16]
- Is 6 < 22 ?   Array=[2,6,27,22,18,16]
- Is 6 < 18 ?   Array=[2,6,27,22,18,16]
- Is 6 < 16 ?   Array=[2,6,27,22,18,16]

- Is 22 < 27 ?  Array=[2,6,22,27,18,16]

- Is 27 < 22 ?  Array=[2,6,22,27,18,16]
- Is 18 < 22 ?  Array=[2,6,18,27,22,16]

- Is 27 < 18 ?  Array=[2,6,18,27,22,16]
- Is 22 < 18 ?  Array=[2,6,18,27,22,16]
- Is 16 < 18 ?  Array=[2,6,16,27,22,18]

- Is 27 < 16 ?  Array=[2,6,16,27,22,18]
- Is 22 < 16 ?  Array=[2,6,16,27,22,18]
- Is 18 < 16 ?  Array=[2,6,16,27,22,18]

- Is 22 < 27 ?  Array=[2,6,16,22,27,18]

- Is 27 < 22 ?  Array=[2,6,16,22,27,18]
- Is 18 < 22 ?  Array=[2,6,16,18,27,22]

- Is 27 < 18 ?  Array=[2,6,16,18,27,22]
- Is 22 < 18 ?  Array=[2,6,16,18,27,22]

- Is 22 < 27 ?  Array=[2,6,16,18,22,27]

- Is 27 < 22 ?  Array=[2,6,16,18,22,27]


## Big O Notation


Big O Notation >>>>>  O(n^2)

## Time Compexity

For worst case: n*(n-1)* .... 1 = n*(n-1)/2  = n^2/2 - n/2
O(n^2)

Best Case: O(n)

Avg Case : O(n^2)

## Which case fits for 18 after array is rearranged?

Starting Array {22,27,16,2,18,6}

Final Array=[2,6,16,18,22,27]

Since we dont ask every element to rearrange 18 and it is not the easiest one, 
furthermore it is on the middle of the array in both starting and final array 
so its avarage case

## First 4 steps of [7,3,5,8,2,9,4,15,6] 

1. Is 3 < 7 ?  Array= [3,7,5,8,2,9,4,15,6] 

2. Is 5 < 3 ?   Array= [3,7,5,8,2,9,4,15,6] 

3. Is 8 < 3 ?   Array= [3,7,5,8,2,9,4,15,6] 

4. Is 2 < 3 ?   Array= [2,7,5,8,3,9,4,15,6] 
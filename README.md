# bubble_sort_py

````py
class Solution:
    #Function to sort the array using bubble sort algorithm.
    # T = O(n^2)
    def bubbleSort(self,arr, n):
        # code here
        for i in range(n): 
            for j in range(n-1): 
                k = j + 1
                if arr[j] > arr[k]: 
                    arr[j], arr[k] = arr[k], arr[j]

````

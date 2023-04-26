# Insertion-Sort  
Insertion sort is a simple sorting algorithm.The array is virtually split into a sorted and an unsorted part.

![insertion-sort-geeksforgeeks](https://user-images.githubusercontent.com/91966613/234469660-0d13cc98-6f22-4a51-bcd5-1f74a50d9dc3.gif)

### Working of Insertion Sort
Values from the unsorted part are picked and placed at the correct position in the sorted part. 
![image](https://user-images.githubusercontent.com/91966613/234469125-efd0cd0a-fb62-4910-b013-3f736569149e.png)  
1. The first element in the array is assumed to be sorted. Take the second element and store it separately in key.  
Compare key with the first element. If the first element is greater than key, then key is placed in front of the first element.  
![image](https://user-images.githubusercontent.com/91966613/234469223-754c9662-fda0-44ba-b901-830e8e2aa4e4.png)  

2. Now, the first two elements are sorted.  
Take the third element and compare it with the elements on the left of it.  
Placed it just behind the element smaller than it.  
If there is no element smaller than it, then place it at the beginning of the array.  
![image](https://user-images.githubusercontent.com/91966613/234469322-4af25f0d-4774-469d-8e41-391079bc1b0f.png)  

3. Similarly, place every unsorted element at its correct position.  
![image](https://user-images.githubusercontent.com/91966613/234469482-75a81e4e-4cbe-44b4-8c16-2d587ba3dae3.png)  

  ![image](https://user-images.githubusercontent.com/91966613/234469591-ed8e0461-d71e-40ee-81f6-b0a6b67cfbef.png)  







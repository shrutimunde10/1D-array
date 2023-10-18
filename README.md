# 1D-array
TITLE: Array in C++

AIM:  

       i) To write a program to search for an element in an array.
       ii) To write a program to declare a matrix in an array and print. 
       iii) To write a program to add a matrix using array. 

THEORY:  In C++, an array is a collection of elements of the same data type stored in contiguous memory locations.
         Each element in the array can be accessed using an index, which starts from 0 for the first element and goes up to the size of the array minus one.
         C++ arrays have fixed sizes determined at compile time. If you need a dynamic-sized container,  consider using other data structures like std::vector or dynamic memory allocation with pointers.

ALGORITHM:  

            1. Start
            2. Declare variables: arr[10] (array to store elements), I, num (element to search),
            n (array size), cnt (counter for an element found), pos (position of element found).
            3. Display "Enter Array Size:".
            4. Read the value of 'n' (array size).
            5. Display "Enter Array Elements:".
            6. Loop 'i' from 0 to 'n-1':
               a. Read and store arr[i] from the user.
            7. Display "Enter element to be searched:".
            8. Read the value of 'num' (element to search).
            9. Loop 'i' from 0 to 'n-1':
               a. If arr[i] is equal to 'num':
               i. Set cnt to 1 (element found).
              ii. Set pos to i+1 (position of the element).
              iii. Break the loop.
            10. If cnt is 0:
                a. Display "Element Not Found!!".
            11. Else:
                  a. Display "Element <num> Found at position <pos>".
            12. End

CONCLUSION: An element in the array is searched and the program is executed successfully.
A matrix is printed using array. Two matrices are added using an array. 

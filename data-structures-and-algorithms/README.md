# Insertion Sort Project

### [22,27,16,2,18,6]

## 1- Insertion Sort Steps

1. [22, 27, 16, 2, 18, 6] .... 1

2. [16, 22, 27, 2, 18, 6]

3. [2, 16, 22, 27, 18, 6]

4. [2, 16, 18, 22, 27, 6] .... n-1

5. [2, 6, 16, 18, 22, 27] .... n

## 2- Big-O Notation

O (n^2)

## 3- Time Complexity

Best Case: n
Avarage Case: n^2
Worst Case: n^2

## 4- Which case for 18?

Since it is in the middle of the array, 18 is in the scope of the average case.

## 5- First 4 Insertion Sort steps

[7, 3, 5, 8, 2, 9, 4, 15, 6]

1. [[3,7,5,8,2,9,4,15,6]

2. [3,5,7,8,2,9,4,15,6]

3. [3,5,7,8,2,9,4,15,6]

4. [3,5,7,2,8,9,4,15,6]

# Merge Sort Project

### [16,21,11,8,12,22] 

## 1- Merge Sort Steps

1. [16,21,11] - [8,12,22]
2. [16,21] - [11] - [8,12] - [22]
3. [16] - [21] - [11] - [8] - [12] - [22]
4. [16,21] - [8,11] - [12,22]
5. [8,11,16,21] - [12,22]
6. [8,11,12,16,21,22]

## 2- Big-O Notation

O (n*(logn))
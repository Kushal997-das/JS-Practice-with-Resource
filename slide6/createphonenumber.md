# Problem Description

You are given an array `arr` of 10 numbers (each number can be between 0 and 9) as an argument. You have to implement the function `createPhoneNumber` which will return a string of those numbers in the form of a phone number.

**Hint 1:** Use a loop to iterate through the array.

**Hint 2:** Use a variable with an initial value as an empty string and then concatenate the elements of the array one by one to form a string which can be returned.

## Sample Input 1

```plaintext
1, 2, 3, 4, 5, 6, 7, 8, 9, 0
```

## Sample Output 1

```plaintext
1234567890
```

**Explanation:**
Given `arr` is 1, 2, 3, 4, 5, 6, 7, 8, 9, 0. Concatenating these we get 1234567890.

## Sample Input 2

```plaintext
9, 8, 7, 6, 5, 4, 3, 2, 1, 0
```

## Sample Output 2

```plaintext
9876543210
```

**Explanation:**
Given `arr` is 9, 8, 7, 6, 5, 4, 3, 2, 1, 0. Concatenating these we get 9876543210.


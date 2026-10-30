
# EX 1B Power of 2
## DATE:
## AIM:
To write a Java program to for given constraints.Given an integer n, return true if it is a power of two. Otherwise, return false.

An integer n is a power of two, if there exists an integer x such that n == 2x.

## Algorithm
1. Start

2. Read an integer value n from the user.

3. If n ≤ 0, then: Output false and stop

4. Compute the value of (n & (n - 1)).

5. If the result is 0, then: Output true else: Output false


## Program:
```
/*
Program to implement Reverse a String
Developed by: Suchitra Nath 
Register Number:  212223220112
*/

import java.util.Scanner;
public class Solution {

    public static boolean isPowerOfTwo(int n) {
        if (n <= 0) return false;
        return (n & (n - 1)) == 0;
     
     
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Solution sol = new Solution();
        int n = scanner.nextInt();

        boolean result = sol.isPowerOfTwo(n);
        System.out.println(result);

        scanner.close();
    }
}

```

## Output:
<img width="427" height="336" alt="image" src="https://github.com/user-attachments/assets/63acbf35-c63d-406c-adfc-ade434c50f5b" />



## Result:
The program successfully implemented and the expected output is verified.

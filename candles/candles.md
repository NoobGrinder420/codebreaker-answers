### candles

### Problem Statement

There are *N* candles placed on a number line. The *i*-th candle from the left is placed on coordinate *xi*. Here, *x1* < *x2* < ... < *xN* holds.

Initially, no candles are burning. Snuke decides to light *K* of the *N* candles.

Now, he is at coordinate 0. He can move left and right along the line with speed 1. He can also light a candle when he is at the same position as the candle, in negligible time.

Find the minimum amount of time to light *K* candles.

### Constraints

-   1 ≤ *N* ≤ 105
-   1 ≤ *K* ≤ N
-   *xi* is an integer
-   |*xi*| ≤ 108
-   *x1* < *x2* < ... < *xN*

### Input

Input is given from Standard Input in the following format:

*N* *K*
*x1* *x2* ... *xN*

### Output

Print the minimum time required to light *K* candles.

### Sample Input 1

5 3
-30 -10 10 20 50

### Sample Output 1

40

He should move and light candles as follows:

-   Move from coordinate 0 to -10.
-   Light the second candle from the left.
-   Move from coordinate -10 to 10.
-   Light the third candle from the left.
-   Move from coordinate 10 to 20.
-   Light the fourth candle from the left.

### Sample Input 2

3 2
10 20 30

### Sample Output 2

20

### Sample Input 3

1 1
0

### Sample Output 3

0

### Sample Input 4

8 5
-9 -7 -4 -3 1 2 3 4

### Sample Output 4

10
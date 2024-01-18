# Marc Loves Cupcakes Readme

## Problem Statement

Marc loves cupcakes, but he also likes to stay fit. Each cupcake has a calorie count, and Marc can walk a distance to expend those calories. After eating a cupcake with *c* calories, he must walk at least *c* miles to maintain his weight. Given the individual calorie counts for each of the cupcakes, determine the minimum number of miles Marc must walk to maintain his weight. Note that he can eat the cupcakes in any order.

### Example

If Marc eats the cupcakes in the order shown, the miles he will need to walk are 1 + 3 + 2 = 6. This is not the minimum, though, so we need to test other orders of consumption. In this case, our minimum miles is calculated as 1 + 2 + 3 = 6. Given the individual calorie counts for each of the cupcakes [1, 3, 2], the minimum miles Marc must walk is 6.

### Function Description

Complete the `marcsCakewalk` function in the editor. It has the following parameter:

```python
marcsCakewalk(calorie: List[int]) -> int
```

**Parameters:**
- `calorie`: A list of integers representing the calorie counts for each cupcake.

**Returns:**
- An integer representing the minimum miles necessary.

### Input Format

The input consists of:
- The first line contains an integer *n*, the number of cupcakes.
- The second line contains *n* space-separated integers, representing the calorie counts for each cupcake.

### Constraints

- 1 ≤ *n* ≤ 40
- 1 ≤ *calorie[i]* ≤ $10^9$

### Sample Input 0

```
3
1 3 2
```

### Sample Output 0

```
11
```

**Explanation 0:**
Let's say the number of miles Marc must walk to maintain his weight is *m*. He can minimize *m* by eating the 3 cupcakes in the following order:
1. Eat the cupcake with 1 calorie, so *m* = 1.
2. Eat the cupcake with 3 calories, so *m* = 1 + 3 = 4.
3. Eat the cupcake with 2 calories, so *m* = 4 + 2 = 6.
We then print the final value of *m*, which is 6, as our answer.

### Sample Input 1

```
4
7 4 9 6
```

### Sample Output 1

```
79
```

**Explanation 1:** *(Details of the explanation can be added based on the problem description.)*

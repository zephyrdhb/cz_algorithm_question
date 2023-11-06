# cz_algorithm_question
cz_algorithm_question

**题目一（排序、查找）：** 在一个无序的整数数组中，找出两个元素的和等于给定目标值的索引。假设输入的数组中一定存在这样的两个元素，并且每个元素只能使用一次。

```python
from typing import List, Tuple

# 函数签名
def find_two_sum(arr: List[int], target: int) -> Tuple[int, int]:
    pass

# 输入和输出
arr = [2, 7, 11, 15]
target = 9
print(find_two_sum(arr, target))  # 输出 (0, 1)

arr = [3, 2, 4]
target = 6
print(find_two_sum(arr, target))  # 输出 (1, 2)
```

**题目二：** 给定一个字符串，编写一个函数将字符串中的所有空格替换为"%20"。要求不能使用内置的字符串替换函数，需要自己实现。

```python
# 函数签名
def replace_space(s: str) -> str:
    pass

# 输入与输出
s = "We are happy."
print(replace_space(s))  # 输出 "We%20are%20happy."

s = "Hello World"
print(replace_space(s))  # 输出 "Hello%20World"
```

**题目三：** 一只青蛙一次可以跳上1级台阶，也可以跳上2级。求该青蛙跳上一个 n 级的台阶总共有多少种跳法（先后次序不同算不同的结果）。

要求：时间复杂度：*O*(*n*) ，空间复杂度：*O*(1)

```python
# 函数签名
def jumpFloor(number: int) -> int:
    pass

# 输入与输出
number = 4
print(jumpFloor(jumpFloor))  # 输出 5
```

**题目四：** 有N件物品和一个容量为V的背包。第i件物品的价值是C[i]，重量是W[i]。求解将哪些物品装入背包可使价值总和最大。

```python
from typing import List, Tuple

# 函数签名
def knapsack(capacity: int, weights: List[int], values: List[int]) -> Tuple[int, List[int]]:
    pass

# 输入与输出
capacity = 10
weights = [2, 3, 4, 5]
values = [3, 4, 5, 6]
print(knapsack(capacity, weights, values))  # 输出：(13, [0, 1, 3])
```


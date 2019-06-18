---
description: Array
---

# 1. Calculate Average of Array

Print sum of items.

Sample Input

```text
3
1 2 3 4 5
2 2 2 2 2
4 6 8 10 12
```

Sample Output

```text
15
10
40
```

{% hint style="info" %}
Use **for loop**.  
Create a variable that tracks the sum of items.
{% endhint %}



{% tabs %}
{% tab title="Python" %}
{% code-tabs %}
{% code-tabs-item title="main.cpp" %}
```python
# Calculate sum for array
def getSum(nums):
  res = 0
  for num in nums:
    res += num
  return res

TC = int(input()) # Test Cases
for _ in range(TC):
  nums = list(map(int, input().split()))
  ans = getSum(nums)
  print(ans)

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Java" %}

{% endtab %}

{% tab title="C++" %}

{% endtab %}
{% endtabs %}


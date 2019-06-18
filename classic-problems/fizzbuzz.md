---
description: Learn mod and if else
---

# FizzBuzz

{% tabs %}
{% tab title="Python" %}
```python
for i in range(1, 101):
    if i % 15 == 0:
        print('FizzBuzz')
    elif i % 5 == 0:
        print('Buzz')
    elif i % 3 == 0:
        print('Fizz')
    else:
        print(i)
```

TODO: Screenshot
{% endtab %}

{% tab title="Java" %}
```java
class Main {
  public static void main(String[] args) {
    for (int i = 1; i <= 100; i++) {
      if (i % 15 == 0) {
        System.out.println("FizzBuzz");
      } else if (i % 5 == 0) {
        System.out.println("Buzz");
      } else if (i % 3 == 0) {
        System.out.println("Fizz");
      } else {
        System.out.println(i);
      }
    }
  }
}
```
{% endtab %}

{% tab title="C++" %}
```cpp
#include<iostream> 
using namespace std; 
  
int main() 
{ 
    for (int i = 1; i <= 100; i++) {
      if (i % 15 == 0) {
        cout << "FizzBuzz\n";
      } else if (i % 5 == 0) {
        cout << "Buzz\n";
      } else if (i % 3 == 0) {
        cout << "Fizz\n";
      } else {
        cout << i << "\n";
      }
    }
      
    return 0; 
} 
```
{% endtab %}
{% endtabs %}




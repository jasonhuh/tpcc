---
description: Practice accepting an input.
---

# 2. What's your name?

Accept a name as input, and print 'My name is \[your name\]'

```text
### Example 1
### Input:
James Bond
### Output: 
Your name is James Bond

```

\[Submit your code here\]

{% hint style="info" %}
Python: Use input\(\) to accept user's input.

Java: Use _Scanner_ class to accept user's input.

C++: Use _cin_ or _scan_ to accept user's input
{% endhint %}

#### Solution

{% tabs %}
{% tab title="Python" %}
{% code-tabs %}
{% code-tabs-item title="main.py" %}
```python
name = input()
print('My name is {}'.format(name)
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Java" %}
{% code-tabs %}
{% code-tabs-item title="Main.java" %}
```java
import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    Scanner in = new Scanner(System.in);
    String name = in.nextLine();
    System.out.println("Your name is " + name);
  }
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="C++" %}
{% code-tabs %}
{% code-tabs-item title="main.cpp" %}
```cpp
#include<iostream> 
using namespace std; 
  
int main() 
{ 
    string name; 
    cin >> name; 
    cout << "Your name is " << name << "\n"; 
      
    return 0; 
} 

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

\[Share your solution\]  
\[Discuss\]


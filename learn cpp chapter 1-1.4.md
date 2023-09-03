變量賦值和初始化

```cpp
int x;    // define an integer variable named x
int y, z; // define two integer variables, named y and z
```


```cpp
#include <iostream>

int main()
{
	int width;
	width = 5; // copy assignment of value 5 into variable width

	std::cout << width; // prints 5

	width = 7; // change value stored in variable width to 7

	std::cout << width; // prints 7

	return 0;
}
```

以上是改變width的值

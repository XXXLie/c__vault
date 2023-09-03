# 1.5 — Introduction to iostream: cout, cin, and endl
詳細的解釋類似std::cout的東西
1. std:cout可以傳送資料到控制台
#include <iostream> // for std::cout

int main()
{
 std::cout << "Hello world!"; // print Hello world! to console

 return 0;
}
<< "Hello world !";
	 運算符號允許我們在控制台上顯示信息
----------------------------------------------------
#include <iostream> // for std::cout

int main()
{
    std::cout << 4; // print 4 to console

    return 0;
}

在控制台上顯示的是4
-----------------------------------------------------
#include <iostream> // for std::cout

int main()
{
    int x{ 5 }; // define integer variable x, initialized with value 5
    std::cout << x; // print value of x (5) to console
    return 0;
}

是5
int x{5}= 自訂議變量 x，初始化值為 5
也可以這樣
#include <iostream> // for std::cout

int main()
{
    int x{ 5 };
    std::cout << "x is equal to: " << x;
    return 0;
}
是5
-----------------------------------------------------
#include <iostream> // for std::cout

int main()
{
    std::cout << "Hi!";
    std::cout << "My name is Alex.";
    return 0;
}
是Hi!My name is Alex.
如果想分行要用std::endl
#include <iostream> // for std::cout and std::endl

int main()
{
    std::cout << "Hi!" << std::endl; // std::endl will cause the cursor to move to the next line of the console
    std::cout << "My name is Alex." << std::endl;

    return 0;
}
是Hi!
My name is Alex
-----------------------------------------------------------------------------------------





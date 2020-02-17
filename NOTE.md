
# 2020 cpp-learning-course

Here is the project/task for my cpp learning

---
## 4.2 Class & Object

### class & object is the base of the project,for great use.
```
    #include<bits\stdc++.h>
    using namespace std;
    class Class{
        int a;
        /*inside variates*/
    pubilc:
        Class();
        ~Class();
        int b;
        /*Funtions/Variates can be use outside*/
    };
    Class::Class(){
        /*Constructor*/
    }
    Class::~Class(){
        /*Destructor*/
    }
```
image:

![example](https://github.com/sysu-19351128/cppclass/image/capture_20200217194204955.jpg)

and next is the private/pubilc/protected
pubilc means it can be visit by outside funtions like:

`std::cout << string/variates << endl;`

```
    funtion{
        Class A;
        A.funtion();
        int c = A.b;  //correct
        int d = A.a;  //wrong
        return ...;
    }
```

and private means it can't be visit by ways of "pubilc",but can be visit by their "friends"

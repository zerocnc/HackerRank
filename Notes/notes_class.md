# Classes within C++

Classes are user defined within C++

It also has access specifiers, which restrict the access of member elements. The primarily used ones are the following:

-    **public**: Public members (variables, methods) can be accessed from anywhere the code is visible.
-    **private**: Private members can be accessed only by other member functions, and it can not be accessed outside of class.

```
class SampleClass {
    private:
        int val;
    public:
        void set(int a) {
            val = a;
        }
        int get() {
            return val;
        }
};
```

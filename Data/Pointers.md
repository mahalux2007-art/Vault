okay see pointers store address of another variable okay

so if i say 

`int x = 4 
x becomes 4


```
int *p=&a;
int y = *p; 
```

\*p is in same line of &
when no star before ==🟡data type== star means the thing inside whats front of it.

no i think it is int \*p then & if not no
and to write value i can do \*p = smtg


also if im in a function and the parameter is a pointer, i gotta give in address
int \*p = &a
but if a in an array i dont gotta use & 
p\[2] is also possible

```
int *bad(void) {
int local = 5;
return &local;
}
```
here the return type is a pointer
```
#include <stdio.h>

struct Dog {
    int age;
};

int main(void) {
    struct Dog my_dog = { 3 };    // A Dog value; its age is 3
    struct Dog *pointer = &my_dog; // Pointer points to my_dog

    printf("%d\n", my_dog.age);   // Use . because my_dog is a struct
    printf("%d\n", pointer->age);  // Use -> because pointer is a pointer

    pointer->age = 4;              // Change my_dog's age through the pointer
    printf("%d\n", my_dog.age);    // Prints 4

    return 0;
}

```

it says s1.age = smtg
i say pointer->age ie s1.=pointer

Stores the number in the new node. The `->` operator accesses a field through a pointer. This is equivalent to `(*new_node).data`.



[[Malloc and shi]]
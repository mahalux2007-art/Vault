[[Dynamic Memory allocation]]

### Malloc

```
int *scores = malloc(5 * sizeof *scores);
```
so we ask computer to make space and store the adress of that space in a pointer alr
and then we say make space for 5 elements in the size of \*scores meaning whatver is inside scores, for now its int
```
pointer = malloc(number_of_bytes);
```
so we just need specifc amount of bytes inside this

```
int numbers[] = {10, 20, 30};
int *p = numbers;

printf("%d\n", *p);       // 10
printf("%d\n", *(p + 1)); // 20
printf("%d\n", p[2]);     // 30


for (int i = 0; i < 5; i++) {
    numbers[i] = 0;
```
so here i can put \*(numbers + i) to also access


### CALLOC

```
pointer = calloc(number_of_elements, size_of_each_element);
```
here we specifically say number of elements


### REALLOC

```
new_pointer = realloc(old_pointer, new_size_in_bytes);
```

changes side of prev allocates space

and then i do free(pointer)
note its not free(\* pointer) X


```
void allocate_int(int **out) {
    *out = malloc(sizeof **out);
}

int *value = NULL;
allocate_int(&value);

```

over heree 
I am askin storage for one integer and saving the memory of that space in another pointer
but why?
here im giving a pointer where address is stored

give me address of where its stored and address off the address place stored



# wait what does \*p inside a function mean?
soo i think it means that im giving you a pointer as parameter right, for user to give  a variable where address is stored uh i dunno i think i give an adress while calling na







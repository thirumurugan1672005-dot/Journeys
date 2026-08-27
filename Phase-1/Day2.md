# Variables
Variables are placeholders for values 

```c
int age; //  variable declared
age = 32;
```

You must intialise the variables before going to use


Variables rules 
1. It contains the letters,digits,underscores
2. It cannot contains spaces , @ like symbols
3. It cannot start with digit
4. We cannot use reserved keywords
5. I recommend use meaningful names either camelcase or snakecase

# printf statement

```c
printf("My name is %s","Rahul");
```

Every statement must ends with semicolon or else compiler will give syntax error

1. Order of format specifier matters in printf statement
```c
printf("%d %s","Rahul",12);// won't execute 
```

2. Number of format specifier is same as this parameters
```c
printf("%d%s",12); // error
```

3. curly braces deine scope

```c
{
int x = 20;
}
```
x gets destroyed at end of curly braces 

# Standard Program

```c
#include<stdio.h>
int main(){
  printf("Hello World");
  return 0;
}
```
1. ```#``` include directives Here include ```#include<stdio.h>``` to include input/output header files
2. int main(){} where the execution of c begins
3. return 0 means , The Program executed Successfully

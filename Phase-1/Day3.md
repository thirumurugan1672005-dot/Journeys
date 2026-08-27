# How to take inputs

scanf function form <stdio.h>

# integer
```c
int n;
scanf("%d",&n);
printf("%d",n);
```
# float
```c
int n;
scanf("%f",&n);
printf("%f",n);
```
# double
```c
int n;
scanf("%lf",&n);
printf("%lf",n);
```
# character
```c
int n;
scanf("%c",&n);
printf("%c",n);
```

# string (one word)
```c
char[100]s;
scanf("%s",s);
printf("%s",s);
```

# string(entire line)

```c
char[100]s;
scanf("%[^\n]%*c,s);// search until newline any number of characters zero or more
printf("%s",s);
```

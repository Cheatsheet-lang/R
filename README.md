# R
R-Cheatsheet

### R is similar to python with some differences in syntax

## Packages

### Installing packages
```python
install.packages('package_name')
```

### Loading Package
```python
library(package_name)         #notice - no quotes
```


## Basic Operations

### Variables
```python
a = 10
b = "hello"
c <- "similar to above one"     # "<-" is similar to '='
```

### Arithmetic Operations
```python
10 + 11
19 * 7
7 / 3
5 ^ 3   #125 - exponential
5 ** 3  #125 - exponential
8 %% 5  #3 - %% indicates x mod y (“x modulo y”)
8 %/% 5 #1 - Integer Division
```

## Conditions

### if - else
```python
if (condition){
    Do something
} else {
    Do something different
}
```


## Loops

### for
```python
for (variable in sequence){
    Do something
}
```
#### Example

```python
for (i in 1:3){
    print(i)
}
```
#### output
```python
1
2
3
```

### while
```python
while (condition){
    Do something
}
```
#### Example

```python
while (i < 10){
    print(i)
    i = i + 1
}
```


## Vectors

### Creating Vector

```python
c(2, 4, 6)      # 2, 4, 6
```

```python
2:6             # 2, 3, 4, 5, 6
```

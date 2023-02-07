# MATLAB Syntax

MATLAB is a numerical computing language that provides a comprehensive suite of mathematical functions. In this section, we will go over some basic syntax in MATLAB.

## Variables

Variables in MATLAB are defined by assigning values to them. For example:

```MATLAB
a = 5;
b = 10;
c = a + b;
```

## Data Types

MATLAB supports several data types including:

* Numeric types (double, single, int8, int16, int32, int64, uint8, uint16, uint32, uint64)
* Logical type (logical)
* Character type (char)
* Cell arrays (cell)
* Structures (struct)
* Tables (table)

## Arrays

Arrays in MATLAB can be created using square brackets `[]` . For example:

    

``` MATLAB
a = [1 2 3 4];
b = [5; 6; 7; 8];

```


## Operators

MATLAB supports a range of arithmetic and logical operators including:

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Power (^)
- Modulo (mod)

## Conditional Statements

Conditional statements in MATLAB are used to make decisions based on conditions. For example:

```MATLAB
a = 5;
b = 10;

if a < b
disp('a is less than b');
elseif a == b
disp('a is equal to b');
else
disp('a is greater than b');
end

```


## Loops

MATLAB supports `for` and `while` loops. For example:

```MATLAB
for i = 1:10
disp(i);
end

```

```MATLAB
i = 1;
while i <= 10
disp(i);
i = i + 1;
end

```

    
## Functions

MATLAB allows the creation of custom functions using the `function` keyword. For example:

```MATLAB
function y = myFunction(x)
y = x^2;
end

```
    
These are just a few basic syntax elements in **MATLAB** generated with the help of **Chat-GPT** by **Open AI**.  For more information on MATLAB, refer to the official **[Documentation](https://www.mathworks.com/help/matlab/index.html)**.

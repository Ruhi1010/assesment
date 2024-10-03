# 1. Input & Output
The communication between an information processing system, such as a computer, and the outside world, possibly a human or another information processing system.

* Python 
* JavaScript
* C++

Now we see examples of how to take input and how to display output in these programming languages.

## Python
When we need some thing to display as output, we use "print" function for display that specific information.
```python print_function
print("Hello World") 
```
```python output
Output: Hello World
```
## JavaScript
In javascript when we need to display something like 'hello world' we use "console.log" function for display the 'hello world'.
```javascript print function
console.log("hello world");
```
```javascript output
Output: hello world
```
## C++
In c++ when we need to print something like 'hello world' we use "cout" function for print the 'hello world'
```c++ print_function
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}
```
```c++ output
Output: Hello World!
```
****************************************************************
# 2. Variables
A variable is any characteristic, number, or quantity that can be measured or counted. A variable may also be called a data item.

* Python 
* Javascript 
* C++

Now here we discuss about variables how to use initialize variables, take input variables and show them as a output in different languages.

## Python 
Python has no command for declaring a variable. Variables do not need to be declared with any particular type, and can even change type after they have been set.
```python variables
x=50         //integer type
y="Ruhi"    //string type
print(x)   //print the value which is store in variable x
print(y)  //print the value which is store in variable y
```
```
Output: 50
        Ruhi
```
## JavaScript
JavaScript Variables can be declared in 4 ways:

* Automatically
* Using 'var'
* Using 'let'
* Using 'const'

1. Always declare variables

2. Always use const if the value should not be changed

3. Always use const if the type should not be changed (Arrays and Objects)

4. Only use let if you can't use const

5. Only use var if you MUST support old browsers.
****************************************************************

* Automatically 
```javascript variable automatically
x = 5;
y = 6;
z = x + y; 
```


* Using 'var'
```javascript variable using var 
var x = 5;
var y = 6;
var z = x + y;
```

* Using 'let'
```javascript variable using let
let x = 5;
let y = 6;
let z = x + y;
```
* Using 'const'
```javascript variable using const
const x = 5;
const y = 6;
const z = x+y;
```
## C++
Variables are containers for storing data values.

In C++, there are different types of variables (defined with different keywords), for example:

* int - stores integers (whole numbers), without decimals, such as 123 or -123
* double - stores floating point numbers, with decimals, such as 19.99 or -19.99
* char - stores single characters, such as 'a' or 'B'. Char values are surrounded by *  single quotes
* string - stores text, such as "Hello World". String values are surrounded by double quotes
* bool - stores values with two states: true or false

```C++ variables
int myNum = 5;               // Integer 
double myFloatNum = 5.99;    // Floating point number 
char myLetter = 'D';         // Character
string myText = "Hello";     // String (text)
bool myBoolean = true;       // Boolean (true or false)
```

****************************************************************
# 3. Conditions
Conditional statements in programming are used to control the flow of a program based on certain conditions. These statements allow the execution of different code blocks depending on whether a specified condition evaluates to true or false, providing a fundamental mechanism for decision-making in algorithms. In this article, we will learn about the basics of Conditional Statements along with their different types.

### 5 Types of Conditional Statements in Programming
* If Conditional Statement
* If-Else Conditional Statement
* if-Else if Conditional Statement
* Switch Conditional Statement
* Ternary Expression Conditional Statement

*******************************************************************
* If Conditional Statement :\
The if statement is the most basic form of conditional statement. It checks if a condition is true. If it is, the program executes a block of code.

### Python

```Python if statement
a = 33
b = 200
if b > a:
  print("b is greater than a") 
```
### JavaScript

```javascript if statement
if (hour < 18) {
  greeting = "Good day";
} 
```
### C++

```c++ if statement
#include <iostream>
using namespace std;

int main() {
  if (20 > 18) {
    cout << "20 is greater than 18";
  }  
  return 0;
}
```
****************************************************************
* If-Else Conditional Statement :\
The if-else statement extends the if statement by adding an else clause. If the condition is false, the program executes the code in the else block.

### Python

```python if-else statement 
a = 200
b = 33
if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
```
### JavaScript 

```javascript if-else statement 
if (hour < 18) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```
### C++

```c++ if-else statement 
#include <iostream>
using namespace std;

int main() {
  int time = 20;
  if (time < 18) {
    cout << "Good day.";
  } else {
    cout << "Good evening.";
  }
  return 0;
}
```
********************************
* if-Else if Conditional Statement :\
The if-else if statement allows for multiple conditions to be checked in sequence. If the if condition is false, the program checks the next else if condition, and so on.

### Python 

```python if-elif statement 
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```

### JavaScript

```javascript if-elseif statement
if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```

### C++

```c++ if-elseif statement 
#include <iostream>
using namespace std;

int main() {
  int time = 22;
  if (time < 10) {
    cout << "Good morning.";
  } else if (time < 20) {
    cout << "Good day.";
  } else {
    cout << "Good evening.";
  }
  return 0;
}
```
****************************************************************
* Switch Conditional Statement :\
The switch statement is used when you need to check a variable against a series of values. It’s often used as a more readable alternative to a long if-else if chain.\
In switch expressions, each block is terminated by a break keyword. The statements in switch are expressed with cases.

### Syntax 

```syntax of switch statement
switch (variable) {
    case value1:
        // code to execute if variable equals value1
        break;
    case value2:
        // code to execute if variable equals value2
        break;
    default:
        // code to execute if variable doesn't match any value
}
```
*****************************************************************

* Ternary Expression Conditional Statement :\
The ternary operator is a shorthand way of writing an if-else statement. It takes three operands: a condition, a result for when the condition is true, and a result for when the condition is false.

### Syntax 
```syntax of ternary expression statement 
condition ? result_if_true : result_if_false
```
****************************************************************

# 4. Loop Expression
In computer programming, a loop is a sequence of instruction s that is continually repeated until a certain condition is reached. Typically, a certain process is done, such as getting an item of data and changing it, and then some condition is checked such as whether a counter has reached a prescribed number. If it hasn't, the next instruction in the sequence is an instruction to return to the first instruction in the sequence and repeat the sequence. If the condition has been reached, the next instruction "falls through" to the next sequential instruction or branches outside the loop. A loop is a fundamental programming idea that is commonly used in writing programs.

## For loop expression
For loop in programming is a control flow structure that iterates over a sequence of elements, such as a range of numbers, items in a list, or characters in a string. The loop is entry-controlled because it determines the number of iterations before entering the loop.

### Python 
```python for loop
sum = 0
for x in [1,2,3,4,5]:
      sum = sum + x

print(sum)
```

### JavaScript 
```javascript for loop
var nums = ['100','300','400','60','40'];
var sum = 0;

for(var i=0; i < nums.length; i++){

    sum += parseInt(nums[i]);

}

console.log(sum);
```

### C++
```c++ for loop
#include<iostream> 
using namespace std;

int main()
{
    int n;
    cout << "Enter a number : "; 
    cin >> n;
    
    int sum=0;
    
    for(int i=1;i<=n;i++) 
        sum+=i;

    cout << sum;

    return 0;
}
```

## Whie loop expression
A while loop in programming is an entry-controlled control flow structure that repeatedly executes a block of code as long as a specified condition is true. The loop continues to iterate while the condition remains true, and it terminates once the condition evaluates to false.

### Python
```python while loop
i = 0
while i < 5:
    print(i, end=" ")
    i += 1
```

### JavaScript
```javascript while loop
let i,  sum = 0
i = 1
while (i<=10){
  
  if(i%2==0){
    sum= sum + i
  }

  i++
}
console.log(sum)
```

### C++
```c++ while loop
#include <iostream>
using namespace std;

int main()
{

    int i = 0;
    while (i < 5) {
        cout << i << " ";
        i++;
    }
    return 0;
}
```
****************************************************************
# Functions 
Functions in Programming is a block of code that encapsulates a specific task or related group of tasks. Functions are defined by a name, may have parameters and may return a value. The main idea behind functions is to take a large program, break it into smaller, more manageable pieces (or functions), each of which accomplishes a specific task.

### Python 
```python function 
def my_function():
  print("Hello from a function")

my_function()
```

### JavaScript
```javascript function
function greet() {
    console.log("Hello World!");
}

greet();

console.log("Outside function");
```

### C++ 
```c++ function
#include <iostream>
using namespace std;

void myFunction() {
  cout << "I just got executed!";
}

int main() {
  myFunction();
  return 0;
}

```
****************************************************************
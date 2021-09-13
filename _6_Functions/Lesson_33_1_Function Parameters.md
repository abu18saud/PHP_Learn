### meaing # Question ---- ## Point

---------------------------------------------------------

## Function Parameters

- Information can be passed to functions through arguments, which are like variables.
- Arguments are specified after the function name, and within the parentheses.
- Arguments are specified after the function name, and within the parentheses.

## Here, our function takes a number, multiplies it by two, and prints the result:

<?php
    function multiplyByTwo($number) {
        $answer = $number * 2;
        echo $answer;
    }
    multiplyByTwo(3);
?>

## You can add as many arguments as you want, as long as they are separated with commas

<?php
    function multiply($num1, $num2) {
        echo $num1 * $num2;
    }
    multiply(3, 6);
?>

## Note

When you define a function, the variables that represent the values that will be passed to it for processing are called parameters. However, when you use a function, the value you pass to it is called an argument.

## comments

A parameter is a variable in a function. When a function is called, the arguments are the data you pass into the function using (). Parameter is a variable in the declaration of the function. Argument is the actual value of this variable that gets passed to function

---------------------------------------------------------

# What output results from the following code?

function test($num) {
    echo $num/2;
}
test(14);

- 7

---------------------------------------------------------
## Default Arguments

Default arguments can be defined for the function arguments.
In the example below, we're calling the function setCounter(). There are no arguments, so it will take on the default values that have been defined.

<?php
    function setCounter($num=10) {
        echo "Counter is ".$num."<br />";
    }
    setCounter(42);  //Counter is 42
    setCounter();  //Counter is 10
?>

## Note

When using default arguments, any defaults should be on the right side of any non-default arguments; otherwise, things will not work as expected.

---------------------------------------------------------

# Fill in the blanks to define the function "myMul", which takes two parameters and prints the product of their multiplication.

function myMul($num1, $num2)  {
	echo $num1 * $num2;
}

---------------------------------------------------------
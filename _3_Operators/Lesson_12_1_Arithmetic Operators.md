### meaing # Question ---- ## Point

---------------------------------------------------------

## Operators
<?php
    $num1 = 8;
    $num2 = 6;

    //Addition
    echo $num1 + $num2; 
    echo "<br />";

    //Subtraction
    echo $num1 - $num2; 
    echo "<br />";

    //Multiplication
    echo $num1 * $num2; 
    echo "<br />";

    //Division
    echo $num1 / $num2; 
    echo "<br />";
?>

---------------------------------------------------------

# Fill in the blanks to subtract one number from the other.

<?php
$num1 = 23;
$num2 = 16;
echo $num1 - $num2;
?>

---------------------------------------------------------
## Modulus
<?php
    $x = 14;
    $y = 3;
    echo $x % $y;
?>

## Notes
If you use floating point numbers with the modulus operator, they will be converted to integers before the operation.

we can use this function for floating number:
<?php $x = 14.2; $y = 3; echo fmod($x , $y); ?> 

---------------------------------------------------------
# What would the value of the variable $num be after the following code?

<?php
$num = 9;
$num = $num%2; 
?>

---------------------------------------------------------
## Increment & Decrement

The increment operators are used to increment a variable's value.
The decrement operators are used to decrement a variable's value.

$x++; // equivalent to $x = $x+1;
$x--; // equivalent to $x = $x-1; 

## Increment and decrement operators either precede or follow a variable.

$x++; // post-increment 
$x--; // post-decrement 
++$x; // pre-increment 
--$x; // pre-decrement

## The difference is that the post-increment returns the original value before it changes the variable, while the pre-increment changes the variable first and then returns the value.

## Example
$a  = 2; $b = $a++; // $a=3,  $b=2
$a  = 2; $b = ++$a; // $a=3,  $b=3

## The increment operators are used to increment a variable's value.

---------------------------------------------------------
# What output results from the following code?
<?php  
$num = 18; 
$num--;
echo $num;
?>

- 17
---------------------------------------------------------






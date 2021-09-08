### meaing # Question ---- ## Point

---------------------------------------------------------
## String
<?php
  $string1 = "Hello world!"; //double quotes
  $string2 = 'Hello world!';  //single quotes
?>

---------------------------------------------------------
## You can join two strings together using the dot ( .) concatenation operator.
For example: echo $s1 . $s2

---------------------------------------------------------
## PHP Integer

An integer is a whole number (without decimals) that must fit the following criteria:
- It cannot contain commas or blanks
- It must not have a decimal point
- It can be either positive or negative

For example: 
<?php
  $int1 = 42; // positive number
  $int2 = -42; // negative number
?>

---------------------------------------------------------
# Fill in the blank to define the variable string:
<?php
$string = "I am learning PHP";
?>

---------------------------------------------------------
## PHP Float

- A float, or floating point number, is a number that includes a decimal point.
<?php
  $x = 42.168;
?>

---------------------------------------------------------
## PHP Boolean
- A Boolean represents two possible states: TRUE or FALSE.
<?php
  $x = true; $y = false;
?>

---------------------------------------------------------
## Most of the data types can be used in combination with one another. In this example, string and integer are put together to determine the sum of two numbers.

<?php
    $str = "10";
    $int = 20;
    $sum = $str + $int;
    echo ($sum);
?>

## PHP automatically converts each variable to the correct data type, according to its value. This is why the variable $str is treated as a number in the addition.

---------------------------------------------------------
# What output results from the following code?
<?php
 $someString = "15";
 $birthyear = 1982;
 echo $someString + $birthyear;
?>
- 1997

---------------------------------------------------------





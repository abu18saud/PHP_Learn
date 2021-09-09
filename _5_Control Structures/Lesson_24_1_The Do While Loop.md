### meaing # Question ---- ## Point

---------------------------------------------------------

## The do...while Loop
The do...while loop will always execute the block of code once, check the condition, and repeat the loop as long as the specified condition is true.

## Syntax:
do {
  code to be executed;
} while (condition is true); 

---------------------------------------------------------

## Warning
Regardless of whether the condition is true or false, the code will be executed at least once, which could be needed in some situations.

---------------------------------------------------------

# How many times will the following code print "Hello"?

$i = 1;
do {  echo "Hello"; }
while($i < 0);

- 1
---------------------------------------------------------

# The example below will write some output, and then increment the variable $i by one. Then the condition is checked, and the loop continues to run, as long as $i is less than or equal to 7.

<?php
    $i = 5;
    do {
        echo "The number is " . $i . "<br/>";
        $i++;
    } while($i <= 7);
?>

---------------------------------------------------------

## Warning
Note that in a do while loop, the condition is tested AFTER executing the statements within the loop. This means that the do while loop would execute its statements at least once, even if the condition is false the first time.

---------------------------------------------------------

# Rearrange the blocks to form a correct do while loop.

$i = 0;
do {
    $i++;
} while ($i < 10);

---------------------------------------------------------
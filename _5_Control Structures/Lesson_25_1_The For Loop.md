## The for Loop

The for loop is used when you know in advance how many times the script should run.

for (init; test; increment) {
   code to be executed;
}

## Parameters:
init: Initialize the loop counter value
test: Evaluates each time the loop is iterated, continuing if evaluates to true, and ending if it evaluates to false
increment: Increases the loop counter value

## Note
increment section of a for loop is not only used to increment the counter. it is also used to decrement the counter value.

------------------------------------------
# Which is the correct syntax for the classic for loop?
- for (expr1; expr2; expr3)

------------------------------------------

## The example below displays the numbers from 0 to 5:

<?php
    for ($a = 0; $a < 6; $a++) {
        echo "Value of a : ". $a . "<br />";
    }
?>

------------------------------------------


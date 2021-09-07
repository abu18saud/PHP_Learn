### meaing # Question ---- ## Point

---------------------------------------------------------
## Variable Variables
$$a is a variable that is using the value of another variable, $a, as its name. The value of $a is equal to "hello". The resulting variable is $hello, which holds the value "Hi!".

## For example:
<?php
    $a = 'hello';
    $hello = "Hi!";
    echo $$a;
?>

---------------------------------------------------------
# Fill in the blank to print ''World'' to the screen.
<?php 
  $Hello = "World";
  $a = "Hello";
  echo $$a; 
?>
### meaing # Question ---- ## Point

---------------------------------------------------------
## Variables Scope
PHP's most used variable scopes are local, global.
A variable declared outside a function has a global scope.
A variable declared within a function has a local scope, and can only be accessed within that function.

## Consider the following example.

# This is erorr
<?php
    $name = 'David';
    function getName() {
        echo $name;
    }
    getName();

?>

---------------------------------------------------------
# In the example, why did we get a PHP error?
- The variable was not defined within the function

---------------------------------------------------------
## The global Keyword
- The global keyword is used to access a global variable from within a function.
To do this, use the global keyword within the function, prior to the variables.

# This is OK
<?php
    $name = 'David';
    function getName() {
        global $name;
        echo $name;
    }
    getName();
?>

---------------------------------------------------------
# What output results from the following code?
<?php 
$num1 = 56;
function  my_func() {
  $num1 = 89;
  echo $num1;
}
my_func();
?>

- 89
---------------------------------------------------------

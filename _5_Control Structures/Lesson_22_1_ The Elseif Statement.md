### meaing # Question ---- ## Point

---------------------------------------------------------
## The Elseif Statement

Use the if...elseif...else statement to specify a new condition to test, if the first condition is false.

# Syntax:

if (condition) {
  code to be executed if condition is true;
} elseif (condition) {
  code to be executed if condition is true;
} else {
   code to be executed if condition is false;
}

# Warning
- You can add as many elseif statements as you want. Just note, that the elseif statement must begin with an if statement.

---------------------------------------------------------
# How many times can an elseif statement be used?
- As many as you want
---------------------------------------------------------
## For example:
<?php
    $age = 21;

    if ($age<=13) {
        echo "Child.";
    } elseif ($age>13 && $age<19) {
        echo "Teenager";
    } else {
        echo "Adult";
}
?>

---------------------------------------------------------
## Warning
We used the logical AND (&&) operator to combine the two conditions and check to determine whether $age is between 13 and 19.
The curly braces can be omitted if there only one statement after the ifelseifelse.
For example:
if($age<=13)
echo "Child";
else
echo "Adult";

---------------------------------------------------------
# Fill in the blanks to print "Male" if the variable "gender" is equal to 0, "Female" if it is equal to 1, and "Undefined" in all other cases.

if($gender == 0)
   echo "Male";
elseif($gender == 1)
   echo "Female";
else
  echo "Undefined";

---------------------------------------------------------
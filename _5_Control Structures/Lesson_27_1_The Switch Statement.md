### meaing # Question ---- ## Point

---------------------------------------------------------

## The switch Statement
The switch statement is an alternative to the if-elseif-else statement.
Use the switch statement to select one of a number of blocks of code to be executed.

## Syntax:

switch (n) {
  case value1:
    //code to be executed if n=value1
    break;
  case value2:
     //code to be executed if n=value2
     break;
  ...
  default:
    // code to be executed if n is different from all labels
}

---------------------------------------------------------

## Using nested if else statements results in similar behavior, but switch offers a more elegant and optimal solution.
---------------------------------------------------------

# The Switch statement is a replacement for...
- if elseif else statement
---------------------------------------------------------
## Consider the following example, which displays the appropriate message for each day.

<?php
    $today = 'Tue';

    switch ($today) {
        case "Mon":
            echo "Today is Monday.";
            break;
        case "Tue":
            echo "Today is Tuesday.";
            break;
        case "Wed":
            echo "Today is Wednesday.";
            break;
        case "Thu":
            echo "Today is Thursday.";
            break;
        case "Fri":
             echo "Today is Friday.";
             break;
        case "Sat":
             echo "Today is Saturday.";
             break;
        case "Sun":
             echo "Today is Sunday.";
             break;
        default:
             echo "Invalid day.";
    }
?>

---------------------------------------------------------
## The break keyword that follows each case is used to keep the code from automatically running into the next case. If you forget the break; statement, PHP will automatically continue through the next case statements, even when the case doesn't match.

---------------------------------------------------------

# Fill in the blanks.
$i = 1;

switch($i) {  
case "1":
    echo 'One';
    break;
case "2":
    echo 'Two';
    break;
}

---------------------------------------------------------

## default
- The default statement is used if no match is found.

<?php
    $x=5;
    switch ($x) {
        case 1:
            echo "One";
            break;
        case 2:
            echo "Two";
            break;
        default:
            echo "No match";
    }
?>

---------------------------------------------------------

## The default statement is optional, so it can be omitted.
---------------------------------------------------------

# What keyword is used to handle cases that are not defined with the case keyword?
- default
---------------------------------------------------------
## Failing to specify the break statement causes PHP to continue executing the statements that follow the case, until it finds a break. You can use this behavior if you need to arrive at the same output for more than one case.

<?php
    $day = 'Wed';

    switch ($day) {
        case 'Mon':
            echo 'First day of the week';
            break;
        case 'Tue':
        case 'Wed':
        case 'Thu':
            echo 'Working day';
            break;
        case 'Fri':
            echo 'Friday!';
            break;
        default:
            echo 'Weekend!';
    }
?>

## The example above will have the same output if $day equals 'Tue', 'Wed', or 'Thu'.
---------------------------------------------------------
# What output results from the following code?
<? php
$mo = "December";
switch ($mo) {
case "July":
    echo "Summer";
break;
case "January":
case "February":
    echo "Winter";
}
?>

- Nothing
---------------------------------------------------------






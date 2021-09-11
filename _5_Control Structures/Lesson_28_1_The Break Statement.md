### meaing # Question ---- ## Point

---------------------------------------------------------

## The break Statement

- As discussed in the previous lesson, the break statement is used to break out of the switch when a case is matched.
If the break is absent, the code keeps running.

## For example:
<?php
    $x=1;
    switch ($x) {
        case 1:
            echo "One";
        case 2:
            echo "Two";
        case 3:
            echo "Three";
        default:
            echo "No match";
    }
?>
## Output : OneTwoThreeNo match

---------------------------------------------------------
## Break can also be used to halt the execution of for, foreach, while, do-while structures.
---------------------------------------------------------

## Notes

1- The break statement ends the current for, foreach, while, do-while or switch and continues to run the program on the line coming up after the loop.
2- A break statement in the outer part of a program (e.g., not in a control loop) will stop the script.

---------------------------------------------------------

# Fill in the blanks to break out of the loop after the number 5 is printed to the screen.

for ($i=0;$i<=50;$i++)  {
  echo $i;
if ($i==5) {    
break;
  }
}
---------------------------------------------------------

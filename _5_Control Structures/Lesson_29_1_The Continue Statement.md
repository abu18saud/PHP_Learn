### meaing # Question ---- ## Point

---------------------------------------------------------

## The continue Statement

- When used within a looping structure, the continue statement allows for skipping over what remains of the current loop iteration. It then continues the execution at the condition evaluation and moves on to the beginning of the next iteration.

## The following example skips the even numbers in the for loop:

<?php
    for ($i=0; $i<10; $i++) {
        if ($i%2==0) {
            continue;
        }
        echo $i . ' ';
    }
?>

---------------------------------------------------------
# Fill in the blanks to print all the numbers from 0 to 15, except for the numbers 10 and 14.

for ($i=0; $i<=15;$i++) {
  if ($i==10 || $i == 14) {    
  continue;
}
  echo $i."<br />";
}

---------------------------------------------------------
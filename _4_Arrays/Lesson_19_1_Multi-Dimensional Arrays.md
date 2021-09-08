### meaing # Question ---- ## Point

---------------------------------------------------------

## Multi-Dimensional Arrays

A multi-dimensional array contains one or more arrays.

The dimension of an array indicates the number of indices you would need to select an element.
- For a two-dimensional array, you need two indices to select an element
- For a three-dimensional array, you need three indices to select an element

## Warning
- Arrays more than three levels deep are difficult to manage.

---------------------------------------------------------
# How many dimensions are possible in a multi-dimensional array?
- As many as you want

---------------------------------------------------------
## Let's create a two-dimensional array that contains 3 arrays:

$people = array(
   'online'=>array('David', 'Amy'),
   'offline'=>array('John', 'Rob', 'Jack'),
   'away'=>array('Arthur', 'Daniel')
);

## To access the elements of the $people array, we must point to the two indices.

<?php
    $people = array(
        'online'=>array('David', 'Amy'),
        'offline'=>array('John', 'Rob', 'Jack'),
        'away'=>array('Arthur', 'Daniel')
);

    echo $people['online'][0];
    echo "<br />";
    echo $people['away'][1];

?>

## Warning
- The arrays in the multi-dimensional array can be both numeric and associative.
---------------------------------------------------------
# Fill in the blanks to declare a two-dimensional array.

<?php

$cars = array (
  'BMW' =>array('X5', 'red', '2013'),
  'AUDI' => array('A4', 'white', '2008')
  );

?>

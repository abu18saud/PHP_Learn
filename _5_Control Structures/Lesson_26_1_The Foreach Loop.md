### meaing # Question ---- ## Point

---------------------------------------------------------
## The foreach Loop

- The foreach loop works only on arrays, and is used to loop through each key/value pair in an array.

---------------------------------------------------------
## There are two syntaxes:

foreach (array as $value) {
  code to be executed;
}
//or
foreach (array as $key => $value) {
   code to be executed;
}

---------------------------------------------------------
## Example:
<?php
    $names = array("John", "David", "Amy");
    foreach ($names as $name) {
        echo $name.'<br />';
    }
?>

## Example 2:
<?php
$names = array("John"=>23, "David"=>25, "Amy"=>18);
 foreach ($names as $name => $value) {
    echo $name. " " .$value. '<br />'; 
}
?>

---------------------------------------------------------
# Fill in the blanks to print the elements of the array using the foreach loop.
$items = array("one", "two", "three");
foreach
($items as $item)   {
   echo $item ."<br />";
}

---------------------------------------------------------
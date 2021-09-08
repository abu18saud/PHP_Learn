### meaing # Question ---- ## Point

---------------------------------------------------------

## Arrays
An array is a special variable, which can hold more than one value at a time.
If you have a list of items (a list of names, for example), storing them in single variables would look like this:

$name1 = "David"; 
$name2 = "Amy"; 
$name3 = "John"; 

## Numeric Arrays
Numeric or indexed arrays associate a numeric index with their values.
The index can be assigned automatically (index always starts at 0), like this:

$names = array("David", "Amy", "John");

As an alternative, you can assign your index manually.

$names[0] = "David";
$names[1] = "Amy";
$names[2] = "John";

## For example:
<?php
    $names = array("David", "Amy", "John");
    echo $names[1];
?>

# Warning
- Remember that the first element in an array has the index of 0, not 1.

---------------------------------------------------------
# What is the index of the first element of the array?
- 0

---------------------------------------------------------

## Numeric Arrays

- You can have integers, strings, and other data types together in one array.

<?php
    $myArray[0] = "John";
    $myArray[1] = "<strong>PHP</strong>";
    $myArray[2] = 21;

   echo "$myArray[0] is $myArray[2] and knows $myArray[1]";
?>

---------------------------------------------------------
# Fill in the blanks to output "PHP is awesome" to the screen.

<?php
$arr[0] = 'PHP';
$arr[1] = 'awesome';
$arr[2] = ' is ';
echo "$arr[0] $arr[2] $arr[1]" ;
?>
---------------------------------------------------------
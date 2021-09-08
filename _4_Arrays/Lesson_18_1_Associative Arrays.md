### meaing # Question ---- ## Point

---------------------------------------------------------
## Associative Arrays
Associative arrays are arrays that use named keys that you assign to them.
There are two ways to create an associative array:

$people = array("David"=>"27", "Amy"=>"21", "John"=>"42");
// or
$people['David'] = "27";
$people['Amy'] = "21";
$people['John'] = "42";

## Warning
- In the first example, note the use of the => signs in assigning values to the named keys.

---------------------------------------------------------

# Which syntax corresponds to the associative array?
- 'key' => value
---------------------------------------------------------

## Use the named keys to access the array's members.
<?php
    $people = array("David"=>"27", "Amy"=>"21", "John"=>"42");

    echo $people['Amy']; 
?>

---------------------------------------------------------
# Fill in the blanks to output the age from the array.
<?php
$man = array("name"=>"John", "age"=>"25");
echo $man['age'];
?>

---------------------------------------------------------
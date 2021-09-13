### meaing # Question ---- ## Point

---------------------------------------------------------
## Return
- A function can return a value using the return statement.
Return stops the function's execution, and sends the value back to the calling code.

## For example:

<?php
    function mult($num1, $num2) {
        $res = $num1 * $num2;
        return $res;
    }

    echo mult(8, 3);
?>

## Note
- Leaving out the return results in a NULL value being returned.
A function cannot return multiple values, but returning an array will produce similar results.

---------------------------------------------------------

# Rearrange the code to create a function which returns the sum of its parameters, and call it for 5 and 6 as its parameters.

function sum($num1, $num2) {
    $sum = $num1 + $num2;
return $sum; }
sum(5, 6);

---------------------------------------------------------
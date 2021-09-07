### meaing # Question ---- ## Point

---------------------------------------------------------
## Constants
- Constants are similar to variables except that they cannot be changed or undefined after they've been defined.
- Begin the name of your constant with a letter or an underscore.
define(name, value, case-insensitive).

---------------------------------------------------------
## Parameters:
- name: Specifies the name of the constant;
- value: Specifies the value of the constant;
- case-insensitive: Specifies whether the constant name should be case-insensitive. Default is false;
---------------------------------------------------------
## Example for case-sensitive:
<?php
    define("MSG", "Hi SoloLearners!");
    echo MSG;
?>

---------------------------------------------------------
## Example case-insensitive:
<?php
    define("MSG", " Hi SoloLearners!", true);
    echo msg;
?>

---------------------------------------------------------
## Note
## No dollar sign ($) is necessary before the constant name.
---------------------------------------------------------
# Fill in the blanks to declare a case-sensitive constant called AGE and assign the value 28 to it.
<?php
define("AGE", 28);
?>


### meaing # Question ---- ## Point

---------------------------------------------------------
## PHP Class Constructor
- PHP provides the constructor magic method __construct(), which is called automatically whenever a new object is instantiated.

<?php
class Person {
    public function __construct() {
        echo "Object created";
    }
}
$p = new Person();
?>

The __construct() method is often used for any initialization that the object may need before it is used. Parameters can be included in __construct() to accept values when the object is created.


# For example:
<?php
class Person {
    public $name;
    public $age;
    public function __construct($name, $age) {
        $this->name = $name;
        $this->age = $age;
    }
}
$p = new Person("David", 42);
echo $p->name;
?>

In the code above, the constructor uses arguments in the new statement to initialize corresponding class properties.


## Note
- You can't write multiple __construct() methods with different numbers of parameters. Different constructor behavior must be handled with logic within a single __construct() method.

---------------------------------------------------------
# Fill in the blanks to implement a constructor method for the User class.

class User {
    public function __construct(){
    echo "constructed";
  }
}

$n = new User();

---------------------------------------------------------

## PHP Class Destructor

Similar to the class constructor, there is a destructor magic method __destruct(), which is automatically called when an object is destroyed.

# For example:

<?php
class Person {
    public function __destruct() {
        echo "Object destroyed";
    }
}
$p = new Person();
?>

This script creates a new Person object. When the script ends the object is automatically destroyed, which calls the destructor and outputs the message "Object destroyed".
To explicitly trigger the destructor, you can destroy the object using the unset() function in a statement similar to: unset($p);

Destructors are useful for performing certain tasks when the object finishes its lifecycle. For example, release resources, write log files, close a database connection, and so on.

PHP releases all resources when a script finishes its execution.

---------------------------------------------------------

# What is the output of the following code?

class TestMe {
  public function __construct() { echo "2"; }
  public function __destruct() { echo "1"; }
}
$test = new TestMe();
unset($test);

- 21

---------------------------------------------------------
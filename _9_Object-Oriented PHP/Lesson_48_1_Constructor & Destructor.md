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


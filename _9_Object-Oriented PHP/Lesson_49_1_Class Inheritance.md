### meaing # Question ---- ## Point

---------------------------------------------------------
## PHP Class Inheritance

Classes can inherit the methods and properties of another class. The class that inherits the methods and properties is called a subclass. The class a subclass inherits from is called the parent class.

Inheritance is achieved using the extends keyword.

## For example:

<?php
class Animal {
    public $name;
    public function hi() {
        echo "Hi from Animal";
    }
}
class Dog extends Animal {
}

$d = new Dog();
$d->hi();

?>

## Notice
Notice all our properties and methods have public visibility.
For added control over objects, declare methods and properties using a visibility keyword. This controls how and from where properties and methods can be accessed.
Check out the next lesson for more on visibility.

---------------------------------------------------------
# Fill in the blanks to define a class Singer that inherits from the Musician class.

class Musician 
{
  public $name;
  public function toPlay() {
    echo "Playing on piano";
  }
}

class Singer extends Musician {

}


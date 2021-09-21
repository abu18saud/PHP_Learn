### meaing # Question ---- ## Point
# https://t.me/CsharpAbdullahAlsalem/266
# https://t.me/CsharpAbdullahAlsalem/267
---------------------------------------------------------

## Classes & Objects in PHP

- Object Oriented Programming (OOP) is a programming style that is intended to make thinking about programming closer to thinking about the real world.
- Objects are created using classes, which are the focal point of OOP.
- The class describes what the object will be, but is separate from the object itself. In other words, a class can be thought of as an object's blueprint, description, or definition.

- Here, Building is a class. It defines the features of a generic building and how it should work.

- The Empire State Building is a specific object (or instance) of that class.

- You can use the same class as a blueprint for creating multiple different objects.

---------------------------------------------------------

# An object is an instance of a class.
- True

---------------------------------------------------------

## PHP Classes

- In PHP, a class can include member variables called properties for defining the features of an object, and functions, called methods, for defining the behavior of an object. A class definition begins with the keyword class, followed by a class name. Curly braces enclose the definitions of the properties and methods belonging to the class.

## For example:

class Person {
  public $age; //property
  public function speak() { //method
    echo "Hi!"
  }
}

- The code above defines a Person class that includes an age property and a speak() method.

## Note
- A valid class name starts with a letter or underscore, followed by any number of letters, numbers, or underscores.
- Check out the next lesson to see how to instantiate objects!


- Notice the keyword public in front of the speak method; it is a visibility specifier.

- The public keyword specifies that the member can be accessed from anywhere in the code.

- There are other visibility keywords and we will learn about them in later lessons.

---------------------------------------------------------
# Fill in the blanks to declare a class Student with a sayHi() method:

class Student {
  public $name;
  public $age;
  public function sayHi() { echo "Hi!"; }
}

---------------------------------------------------------
# PHP Objects

- The process of creating an object of a class is called instantiation.
To instantiate an object of a class, use the keyword new, as in 
## the example below:

$bob = new Person();

- In the code above, $bob is an object of the Person class.

- To access the properties and methods of an object, use the arrow (->) construct, as in:

echo $bob->age;

- This statement outputs the value of the age property for $bob. If you want to assign a value to a property use the assignment operator = as you would with any variable.


- Let's define the Person class, instantiate an object, make an assignment, and call the speak() method:

<?php
class Person {
    public $age;
    function speak() {
        echo "Hi!";
    }
}
$p1 = new Person(); 
$p1->age = 23;
echo $p1->age; 
$p1->speak();
?>

---------------------------------------------------------




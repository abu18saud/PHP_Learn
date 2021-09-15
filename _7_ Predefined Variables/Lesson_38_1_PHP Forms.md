### meaing # Question ---- ## Point

# https://api.sololearn.com/DownloadFile?id=2379
---------------------------------------------------------

## Forms

- The purpose of the PHP superglobals $_GET and $_POST is to collect data that has been entered into a form.
The example below shows a simple HTML form that includes two input fields and a submit button:

<form action="first.php" method="post">
  <p>Name: <input type="text" name="name" /></p>
  <p>Age: <input type="text" name="age" /></p>
  <p><input type="submit" name="submit" value="Submit" /></p>
</form>

## Note
The purpose of the PHP superglobals $_GET and $_POST is to collect data that has been entered into a form.

---------------------------------------------------------

# Which HTML element is needed to collect user input from a web page?

- form

---------------------------------------------------------

## The action attribute specifies that when the form is submitted, the data is sent to a PHP file named first.php.

## HTML form elements have names, which will be used when accessing the data with PHP.


## Note
- The method attribute will be discussed in the next lesson. For now, we'll set the value to "post".

---------------------------------------------------------

# Which form attribute indicates the page to which the form is submitted?

- Action

---------------------------------------------------------

# Now, when we have an HTML form with the action attribute set to our PHP file, we can access the posted form data using the $_POST associative array.
In the first.php file:

<html>
<body>

Welcome <?php echo $_POST["name"]; ?><br />
Your age: <?php echo $_POST["age"]; ?>

</body>
</html>

The $_POST superglobal array holds key/value pairs. In the pairs, keys are the names of the form controls and values are the input data entered by the user.

# Note

We used the $_POST array, as the method="post" was specified in the form.

---------------------------------------------------------

# Fill in the blanks to submit the form to a page called my.php using the POST method.

<form action="my.php" method="post">
 </form>

--------------------------------------------------------- 
### meaing # Question ---- ## Point

---------------------------------------------------------
## Sessions

- Using a session, you can store information in variables, to be used across multiple pages.
- Information is not stored on the user's computer, as it is with cookies.
- By default, session variables last until the user closes the browser.
---------------------------------------------------------

## Start a PHP Session
A session is started using the session_start() function.
Use the PHP global $_SESSION to set session variables.

## Example
<?php
// Start the session
session_start();

$_SESSION['color'] = "red";
$_SESSION['name'] = "John";
?>

## Now, the color and name session variables are accessible on multiple pages, throughout the entire session.


# Note
The session_start() function must be the very first thing in your document. Before any HTML tags.

---------------------------------------------------------

# Type in the function that must be called before working with the session variables.
- session_start();

---------------------------------------------------------
## Session Variables

Another page can be created that can access the session variables we set in the previous page:

## Example:

<?php
// Start the session
session_start();
?>
<!DOCTYPE html>
<html>
<body>
<?php
echo "Your name is " . $_SESSION['name'];
// Outputs "Your name is John"
?>
</body>
</html>

## Note Very necessary
- Your session variables remain available in the $_SESSION superglobal until you close your session.
- All global session variables can be removed manually by using session_unset().
- You can also destroy the session with session_destroy().
---------------------------------------------------------

# Rearrange the code to declare the variable name, add it to the session, and then print it to the screen.

- session_start();
- $name = "Alex";
- $_SESSION['name'] = $name;
- echo $_SESSION['name'];

---------------------------------------------------------
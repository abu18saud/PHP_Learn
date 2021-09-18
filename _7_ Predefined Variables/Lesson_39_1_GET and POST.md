### meaing # Question ---- ## Point

---------------------------------------------------------

## POST

The two methods for submitting forms are GET and POST.
Information sent from a form via the POST method is invisible to others, since all names and/or values are embedded within the body of the HTTP request. Also, there are no limits on the amount of information to be sent.
Moreover, POST supports advanced functionality such as support for multi-part binary input while uploading files to the server.
However, it is not possible to bookmark the page, as the submitted values are not visible.

## Note

POST is the preferred method for sending form data.

---------------------------------------------------------

# Fill in the blanks to print the value of a text box named "email", which was submitted using POST.

<?php
   echo $_POST["email"];
?>

---------------------------------------------------------

## GET

Information sent via a form using the GET method is visible to everyone (all variable names and values are displayed in the URL). GET also sets limits on the amount of information that can be sent - about 2000 characters.
However, because the variables are displayed in the URL, it is possible to bookmark the page, which can be useful in some situations.

## For example:

<form action="actionGet.php" method="get">
  Name: <input type="text" name="name" /><br /><br />
  Age: <input type="text" name="age" /><br /><br />
  <input type="submit" name="submit" value="Submit" />
</form>

## actionGet.php

<?php
echo "Hi ".$_GET['name'].". ";
echo "You are ".$_GET['age']." years old.";
?>

---------------------------------------------------------
## Warning:
1 - GET should NEVER be used for sending passwords or other sensitive information!
2- When using POST or GET, proper validation of form data through filtering and processing is vitally important to protect your form from hackers and exploits!

---------------------------------------------------------

# Which method was used for the following URL?
# http://www.sololearn.com/index.php?id=825
- GET

---------------------------------------------------------
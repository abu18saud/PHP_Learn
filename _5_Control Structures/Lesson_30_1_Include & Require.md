### meaing # Question ---- ## Point

---------------------------------------------------------
## include

The include and require statements allow for the insertion of the content of one PHP file into another PHP file, before the server executes it.
Including files saves quite a bit of work. You can create a standard header, footer, or menu file for all of your web pages. Then, when the header is requiring updating, you can update the header include file only.

## Assume that we have a standard header file called header.php.
<?php
  echo '<h1>Welcome</h1>';
?>

## Use the include statement to include the header file in a page.
<html>
  <body>

  <?php include 'header.php'; ?>

  <p>Some text.</p>
  <p>Some text.</p>
  </body>
</html>


## The include and require statements allow for the insertion of the content of one PHP file into another PHP file, before the server executes it.

---------------------------------------------------------

# Which is the correct syntax for the include statement in PHP?
- include 'file.php';
---------------------------------------------------------

## Using this approach, we have the ability to include the same header.php file into multiple pages.

<html>
  <body>

  <?php include 'header.php'; ?>

  <p>This is a paragraph</p>
  </body>
</html>

---------------------------------------------------------

# Fill in the blank to include the file header.php
- include  'header.php';

---------------------------------------------------------

# include vs require

The require statement is identical to include, the exception being that, upon failure, it produces a fatal error.
When a file is included using the include statement, but PHP is unable to find it, the script continues to execute.
In the case of require, the script will cease execution and produce an error.

# Note
Use require when the file is required for the application to run.
Use include when the file is not required. The application should continue, even when the file is not found.

---------------------------------------------------------

# What is the difference between include and require?
- The way they handle errors

---------------------------------------------------------
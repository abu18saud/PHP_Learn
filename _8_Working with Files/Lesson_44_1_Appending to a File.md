### meaing # Question ---- ## Point

---------------------------------------------------------

If you want to append content to a file, you need to open the file in append mode.

## For example:

$myFile = "test.txt";
$fh = fopen($myFile, 'a');
fwrite($fh, "Some text");
fclose($fh);

## Note:

When appending to a file using the 'a' mode, the file pointer is placed at the end of the file, ensuring that all new data is added at the end of the file.

---------------------------------------------------------

# Which of the following is not a supported file access mode for the fopen function?

- d

---------------------------------------------------------

## Appending to a File

- Let's create an example of a form that adds filled-in data to a file.

<?php
if(isset($_POST['text'])) {
  $name = $_POST['text'];
  $handle = fopen('names.txt', 'a');
  fwrite($handle, $name."\n");
  fclose($handle); 
}
?>
<form method="post">
  Name: <input type="text" name="text" /> 
  <input type="submit" name="submit" />
</form>

- Now, each time a name is entered and submitted, it's added to the "names.txt" file, along with a new line.

- The isset() function determined whether the form had been submitted, as well as whether the text contained a value.

- We did not specify an action attribute for the form, so it will submit to itself.
---------------------------------------------------------

# Fill in the blanks to open the file using append mode, write to it, and close it.

$h = fopen('my.txt', 'a');
fwrite($h, 'test');
fclose($h);

---------------------------------------------------------
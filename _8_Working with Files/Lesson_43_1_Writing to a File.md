### meaing # Question ---- ## Point

---------------------------------------------------------
## Manipulating Files

- PHP offers a number of functions to use when creating, reading, uploading, and editing files.

- The fopen() function creates or opens a file. If you use fopen() with a file that does not exist, the file will be created, given that the file has been opened for writing (w) or appending (a).

Use one of the following modes to open the file.
### r:
Opens file for read only.

### w:
Opens file for write only. Erases the contents of the file or creates a new file if it doesn't exist.

### a:
Opens file for write only.

### x:
Creates new file for write only.

### r+:
Opens file for read/write.

### w+:
Opens file for read/write. Erases the contents of the file or creates a new file if it doesn't exist.

### a+:
Opens file for read/write. Creates a new file if the file doesn't exist

### x+:
Creates new file for read/write.

## The example below creates a new file, "file.txt", which will be created in the same directory that houses the PHP code.

$myfile = fopen("file.txt", "w");

---------------------------------------------------------
# Drag and drop from the options below to open a file called 'test.txt' for writing.

- fopen("test.txt", "w");
---------------------------------------------------------

## Write to File

When writing to a file, use the fwrite() function.
The first parameter of fwrite() is the file to write to; the second parameter is the string to be written.

The example below writes a couple of names into a new file called "names.txt".


## Example
<?php
$myfile = fopen("names.txt", "w");

$txt = "John\n";
fwrite($myfile, $txt);
$txt = "David\n";
fwrite($myfile, $txt);

fclose($myfile);

/* File contains:
John
David
*/
?>

- Notice that we wrote to the file "names.txt" twice, and then we used the fclose() function to close the file.

- The \n symbol is used when writing new lines.

---------------------------------------------------------

# What is the symbol for a new line in a text file?
- \n

---------------------------------------------------------

## fclose()

- The fclose() function closes an open file and returns TRUE on success or FALSE on failure.
- It's a good practice to close all files after you have finished working with them.
---------------------------------------------------------
# Rearrange the code to write 12 to the file 'num.txt'.

$handle = fopen('num.txt', 'w');
fwrite($handle, '1');
fwrite($handle, '2');
fclose($handle);

---------------------------------------------------------
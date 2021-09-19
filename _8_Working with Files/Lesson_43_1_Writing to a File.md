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



### meaing # Question ---- ## Point

## This graphic shows the main elements of $_SERVER.
- https://t.me/CsharpAbdullahAlsalem/260
---------------------------------------------------------

## $_SERVER

$_SERVER['HTTP_HOST'] returns the Host header from the current request.

<?php
echo $_SERVER['HTTP_HOST'];
//Outputs "localhost"
?>

## This method can be useful when you have a lot of images on your server and need to transfer the website to another host. Instead of changing the path for each image, you can do the following:
- Create a config.php file, that holds the path to your images:

<?php
$host = $_SERVER['HTTP_HOST'];
$image_path = $host.'/images/';
?>

## Use the config.php file in your scripts:

<?php
require 'config.php';
echo '<img src="'.$image_path.'header.png" />';
?>

---------------------------------------------------------

## Note

- The path to your images is now dynamic. It will change automatically, based on the Host header.

- $_SERVER['HTTP_HOST'] returns the Host header from the current request.

---------------------------------------------------------
# What is the $_SERVER variable?
- An array
---------------------------------------------------------
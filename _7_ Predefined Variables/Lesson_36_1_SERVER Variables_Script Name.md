### meaing # Question ---- ## Point

## https://www.w3schools.com/php/php_superglobals.asp
---------------------------------------------------------

## Predefined Variables

A superglobal is a predefined variable that is always accessible, regardless of scope. You can access the PHP superglobals through any function, class, or file.

PHP's superglobal variables are $_SERVER, $GLOBALS, $_REQUEST, $_POST, $_GET, $_FILES, $_ENV, $_COOKIE, $_SESSION.

$_SERVER

$_SERVER is an array that includes information such as headers, paths, and script locations. The entries in this array are created by the web server.
# $_SERVER['SCRIPT_NAME'] returns the path of the current script:
<?php
    echo $_SERVER['SCRIPT_NAME'];
?>

---------------------------------------------------------
# Fill in the blank to print the current script's file path to the screen.

<?php
  $addr = $_SERVER['SCRIPT_NAME'];
  echo $addr;
?>

---------------------------------------------------------
# comments

<?php $indicesServer = array('PHP_SELF', 'argv', 'argc', 'GATEWAY_INTERFACE', 'SERVER_ADDR', 'SERVER_NAME', 'SERVER_SOFTWARE', 'SERVER_PROTOCOL', 'REQUEST_METHOD', 'REQUEST_TIME', 'REQUEST_TIME_FLOAT', 'QUERY_STRING', 'DOCUMENT_ROOT', 'HTTP_ACCEPT', 'HTTP_ACCEPT_CHARSET', 'HTTP_ACCEPT_ENCODING', 'HTTP_ACCEPT_LANGUAGE', 'HTTP_CONNECTION', 'HTTP_HOST', 'HTTP_REFERER', 'HTTP_USER_AGENT', 'HTTPS', 'REMOTE_ADDR', 'REMOTE_HOST', 'REMOTE_PORT', 'REMOTE_USER', 'REDIRECT_REMOTE_USER', 'SCRIPT_FILENAME', 'SERVER_ADMIN', 'SERVER_PORT', 'SERVER_SIGNATURE', 'PATH_TRANSLATED', 'SCRIPT_NAME', 'REQUEST_URI', 'PHP_AUTH_DIGEST', 'PHP_AUTH_USER', 'PHP_AUTH_PW', 'AUTH_TYPE', 'PATH_INFO', 'ORIG_PATH_INFO') ; echo '<table cellpadding="10">' ; foreach ($indicesServer as $arg) { if (isset($_SERVER[$arg])) { echo '<tr><td>'.$arg.'</td><td>' . $_SERVER[$arg] . '</td></tr>' ; } else { echo '<tr><td>'.$arg.'</td><td>-</td></tr>' ; } } echo '</table>' ; ?>

---------------------------------------------------------
# php-str_split-strip_tags
<?php
//Str_split and strip_tags
$a = "hello bangladesh";
print_r(str_split($a));
echo "<br>";
$x= "Hello <b>Bangladesh</b>";
echo strip_tags($x);
?>

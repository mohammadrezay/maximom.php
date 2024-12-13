# maximom.php
https://quera.org/problemset/588?tab=description
<?php
$n = (int)readline("Enter a number: ");
list($n1, $n2, $n3, $n4, $n5, $n6, $n7, $n8, $n9, $n10) = explode(" ",readline("Enter $n numbers: "));
$n1 = (int)$n1;
$n2 = (int)$n2;
$n3 = (int)$n3;
$n4 = (int)$n4;
$n5 = (int)$n5;
$n6 = (int)$n6;
$n7 = (int)$n7;
$n8 = (int)$n8;
$n9 = (int)$n9;
$n10 = (int)$n10;
echo max($n1, $n2, $n3, $n4, $n5, $n6, $n7, $n8, $n9, $n10);

<?php
$number = 7; // Change this number to generate the multiplication table for a different number

echo "Multiplication table for $number:\n";

for ($i = 1; $i <= 10; $i++) {
    $result = $number * $i;
    echo "$number x $i = $result\n";
}
?>

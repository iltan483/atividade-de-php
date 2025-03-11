questao 1
<?php
$a= 100;
$b=70;
$b=(2 * $m) - $a;
echo $b; 

questao 2
<?php

list($N, $H) = explode(' ', trim(fgets(STDIN)));
$alturas = explode(' ', trim(fgets(STDIN)));
$count = 0;

foreach ($alturas as $altura) {
    if ($altura <= $H) {
        $count++;
    }
}
echo $count

questao 3
<?php
$c = 100;
$a = 87;

$resposta = ceil($a / ( $c - 1));
echo $resposta;


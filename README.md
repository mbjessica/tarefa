<?php
echo "Por favor digite um numero inteiro" . PHP_EOL;

$numero = readline ('Numero');

if ($numero %2 == 0){
  echo "O numero é par". PHP_EOL;
}
else {
  echo "O numero é impar" . PHP_EOL;
};

<?php

//1
for ($i = 1; $i <= 10; $i++) {
    echo $i . " ";
}
echo "\n\n";

//2
for ($i = 10; $i >= 1; $i--) {
    echo $i . " ";
}
echo "\n\n";

//3
$suma3 = 0;
for ($i = 1; $i <= 10; $i++) {
    $suma3 += $i;
}
echo $suma3 . "\n\n";

//4
for ($i = 1; $i <= 10; $i++) {
    echo ($i * 2) . " ";
}
echo "\n\n";

//5
$X5 = 12;
$Y5 = 500;
$kwota5 = 0;
for ($m = 1; $m <= $X5; $m++) {
    $kwota5 += $Y5;
    $kwota5 += $kwota5 * 0.08;
}
echo round($kwota5, 2) . "\n\n";

//6
$suma6 = 0;
$element6 = 5;
for ($i = 1; $i <= 100; $i++) {
    $suma6 += $element6;
    $element6 += 10;
}
echo $suma6 . "\n\n";

//7
$cegly7 = 0;
for ($bok = 10; $bok >= 1; $bok--) {
    $cegly7 += $bok * $bok;
}
echo $cegly7 . "\n\n";

//8
$X8 = 20;
$Y8 = 5;
$Z8 = 2;
$razem_cegiel8 = 0;
$aktualny_rzad8 = $X8;
for ($r = 1; $r <= $Y8; $r++) {
    if ($aktualny_rzad8 < 0) $aktualny_rzad8 = 0;
    $razem_cegiel8 += $aktualny_rzad8;
    $aktualny_rzad8 -= $Z8;
}
echo $razem_cegiel8 . "\n\n";

//9
$K9 = 3.5;
$waga_total9 = $razem_cegiel8 * $K9;
echo $waga_total9 . "\n\n";

//10
$a10 = 12;
$b10 = 4;
$operator10 = '+';
switch ($operator10) {
    case '+': echo $a10 + $b10; break;
    case '-': echo $a10 - $b10; break;
    case '*': echo $a10 * $b10; break;
    case '/': echo ($b10 != 0) ? ($a10 / $b10) : "0"; break;
}
echo "\n\n";

//11
$N11 = 10;
$X11 = 5;
$Y11 = 3;
$aktualny11 = $X11;
for ($i = 1; $i <= $N11; $i++) {
    echo $aktualny11 . " ";
    $aktualny11 += $Y11;
}
echo "\n\n";

//12
$pary12 = [[5, 3], [2, -2]];
foreach ($pary12 as $para) {
    $suma = $para[0] + $para[1];
    echo $suma . " ";
    if ($suma == 0) break;
}
echo "\n\n";

//13
$liczba13 = 5;
$silnia13 = 1;
for ($i = 1; $i <= $liczba13; $i++) {
    $silnia13 *= $i;
}
echo $silnia13 . "\n\n";

//14
$n14 = 5;
$start14 = 2;
$liczba14 = $start14;
for ($i = 1; $i <= $n14; $i++) {
    echo $liczba14 . " ";
    $liczba14 = $liczba14 * $liczba14;
}
echo "\n\n";

//15
$suma15 = 0;
for ($i = 1; $i <= 10; $i++) {
    $losowa = rand(50, 100);
    echo $losowa . " ";
    $suma15 += $losowa;
}
$srednia15 = $suma15 / 10;
echo "\n" . $suma15 . " " . $srednia15 . "\n";

?>

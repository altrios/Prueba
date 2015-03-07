<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Documento sin título</title>
</head>

<body>
<?php
$columnas = 5;
$filas = 4;
 
$j = 0;
 
echo "<table style='border: 1px solid #000;'>";
 
while($j < $filas) {
    $i = 0;
    echo "<tr>";
        while($i < $columnas) {
            echo "<td>$j,$i</td>";
            $i++;
        }
    echo "</tr>";
    $j++;
}
 
echo "</table>"; 
?>

</body>
</html>

# lm-sensors output in PHP
creaded by https://github.com/divinity76 (https://stackoverflow.com/users/1067003/hanshenrik)

## usage:
```php
<?php
  include_once('readsensors.php');
  print_r(read_sensors);
?>
```
```php
<?php
  include_once('readsensors.php');
  $cpu_temp = read_sensors();
  print_r($cpu_temp[0]['temp1']['input']);
?>
```

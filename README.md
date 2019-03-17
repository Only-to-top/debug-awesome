# Debug awesome

```php
// Красивая распечатка массива
function debug($arr) {
  echo '<pre>' . print_r($arr, true) . '</pre>';
}

// Подключим функцию
require_once '/filename.php';

// Использование
debug(...);
```

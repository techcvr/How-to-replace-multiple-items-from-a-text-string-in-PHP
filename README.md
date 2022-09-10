# How-to-replace-multiple-items-from-a-text-string-in-PHP


```php
// Provides: You should eat pizza, beer, and ice cream every day
$phrase  = "You should eat fruits, vegetables, and fiber every day.";
$healthy = ["fruits", "vegetables", "fiber"];
$yummy   = ["pizza", "beer", "ice cream"];

$newPhrase = str_replace($healthy, $yummy, $phrase);

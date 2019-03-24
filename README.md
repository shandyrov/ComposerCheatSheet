# To use third-party recipes, you must do the following:

```php
composer config extra.symfony.allow-contrib true
```

### Or add in composer.json

```php
"extra": {
        "symfony": {
          "allow-contrib": "true"
        }
```        

# Remove package
```php
composer remove vendor/package
```

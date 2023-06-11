# Laravel class access wrapper

## Installation:
  ```shell
composer require mphpmaster/laravel-class-access-wrapper
```

## Usage:
```php
$class = new \MPhpMaster\LaravelClassAccessWrapper\ClassAccessWrapper(\Illuminate\Http\Request::class);
dd(
  $class->id, // get property
  $class->all(), // call method
  isset($class->id), // check property is exist
  ($class->id = 1), // set property 
);
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

The Laravel Helpers is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

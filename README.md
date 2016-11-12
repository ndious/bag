# \BSFP\S

## install

```bash

composer require bsfp/bag
```

## API

Configuration

> index.php

```php
<?php

require('vendor/autoload.php');

$bag = new \BSFP\B(['hello' => 'world']);

echo $bag->get('non_existant', 'Hello');
echo ' ';
echo $bag->get('hello');
```

result:

> php index.php

```bash

Hello world

```
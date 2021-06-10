<img src="https://images.unsplash.com/photo-1516616370751-86d6bd8b0651?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=720&h=200">

```php
<?php

use Illuminate\Support\Facades\Route;

Route::get('/', function () {
    return [
        'country' => 'Malaysia',
        'working_on' => ['jeekie.host'],
        'learning' => ['Javascript', 'Typescript', 'React', 'Node.js', 'Golang', 'Java', 'PHP', 'Laravel'],
        'tools' => ['MySQL', 'Nginx', 'Docker'],
        'discord' => [
            'tag' => 'Zake#4304',
            'server' => null,
        ],
    ];
});
```

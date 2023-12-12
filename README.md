![Hola, soy Paul.](https://www.pauljimenez.xyz/img/2.jpg)
```php
<?php

namespace App\Http\Controllers;

use App\Models\Grade;
use Illuminate\Http\Request;

class GradeController extends Controller
{
    public function __construct()
    {
        $this->middleware('auth');
    }
}
```

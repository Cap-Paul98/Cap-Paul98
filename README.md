<h2> Hi, I'm Paul Jiménez! :vulcan_salute:</h2>
<img src="https://www.pauljimenez.xyz/img/2.jpg" width="100%">

[![Twitter: S. Paul Jimenez](https://img.shields.io/twitter/follow/jp_jimenez98?style=social)](https://twitter.com/jp_jimenez98)
[![Linkedin: Paul Jimenez](https://img.shields.io/badge/-PaulJimenez-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/paul-jimenez-developer/)](https://www.linkedin.com/in/paul-jimenez-developer/)
[![WebSite: Paul Jimenez](https://img.shields.io/static/v1?label=&labelColor=505050&message=WebSite&color=%7289DA&style=flat&logo=google-chrome&logoColor=%7289DA)](https://www.pauljimenez.xyz/)

```php
<?php

namespace Life\Learning\FullStackDeveloper;

use Illuminate\Brain\CV;

class CoffeBar extends HechoConCafé
{
    public $about_me;

    function __construct() {
        $this->about_me = [
            'nickname' => 'Captain',
            'code_mains' => 'Php, C#, JavaScript, SQL, HTML, CSS',
            'code_secondary' => 'Java, Dart, C, C++, Delphi, Pascal',
            'frameworks' => 'Laravel, Bootstraps, TailwindCSS, JQuery, AlpineJS, Flutter, EntityFramework',
            'sgdb' => 'SQL Server, MySQL, HeidiSQL, phpMyAdmin',
            'tools' => 'Visual Studio, VS code, Sublime Text, Brackets Editor, laragon, git',
            'systems_operator' => 'SAP B1 (operator and integrator)'
        ];
    }

    function index() : CV {
        $cv = new CV($this->about_me);
        return $cv;
    }
}
```

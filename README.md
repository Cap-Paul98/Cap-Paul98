<h2> Hi, I'm Paul Jiménez! :vulcan_salute:</h2>
<img src="https://lh3.googleusercontent.com/pw/ABLVV852lSzdZoebh-Avq6HID7AYHCsDzGFqXyfSJTmNkfHU1IpNiOizD0Upj-yswjAnhnF7XRSl21S0NL_GAdtcAtc9N15I76e-_7BNtPex1EGXPT2Xnsr9cbf7fjEFjRCfVmxtntWxhF1Jwm3W2xItKtRDMA=w1500-h500-s-no-gm" width="100%">

[![Twitter: S. Paul Jimenez](https://img.shields.io/twitter/follow/jp_jimenez98?style=social)](https://twitter.com/jp_jimenez98)
[![Linkedin: Paul Jimenez](https://img.shields.io/badge/-PaulJimenez-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/paul-jimenez-developer/)](https://www.linkedin.com/in/paul-jimenez-developer/)
[![WebSite: Paul Jimenez](https://img.shields.io/static/v1?label=&labelColor=505050&message=WebSite&color=%230076D6&style=flat&logo=google-chrome&logoColor=%230076D6)](https://www.pauljimenez.xyz/)

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

    function aboutMe() : CV {
        $cv = new CV($this->about_me);
        return $cv;
    }
}
```

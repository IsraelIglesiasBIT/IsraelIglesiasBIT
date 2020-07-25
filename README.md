### Hi there 👋

I´m Israel Iglesias, CTO in /conwork.
<img align="right" src="https://conwork.io/assets/img/conwork.gif" height="50"> 

[![Linkedin: IsraelIglesias](https://img.shields.io/badge/-israeliglesias-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/israeliglesias/)](https://www.linkedin.com/in/IsraelIglesias/)
![GitHub followers](https://img.shields.io/github/followers/IsraelIglesiasBIT?label=IsraelIglesias&style=social)

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=IsraelIglesiasBIT&count_private=true&show_icons=true&theme=prussian&hide=contribs,prs)

```php
<?php

namespace IsraelIglesias;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => '/conwork',
                'position' => 'CTO'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Typescript::class,
            Css::class,
            MariaDB::class,
            MySQL::class,
            Slim::class,
            Laravel::class,
        ];
    }

    public function getFutureGoal()
    {
        return [
            Vuejs::class,
            Python::class,
        ];
    }
}
```

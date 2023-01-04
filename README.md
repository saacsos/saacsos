# 👋 Hi, I’m @saacsos

[![GitHub saacsos](https://img.shields.io/github/followers/saacsos?label=follow&style=social)](https://github.com/saacsos)

[![GitHub Streak](https://streak-stats.demolab.com?user=saacsos&theme=github-light&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

```php
<?php

namespace Saacsos;

public class Me implements About {
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Kasetsart University',
                'position' => 'Computer Technical Officer',
                'duty' => 'Laboratory Instructor',
            ]
        ];
    }
    
    public function getKnowledges(): array
    {
        return [
            Php::class,
            JavaScript::class,
            Laravel::class,
            Vuejs::class,
            TailwindCss::class,
            Python::class,
            Java::class,
            Cpp::class,
            Tex::class,
        ];
    }
    
    public function getGames(): array
    {
        return [
            'Yu-Gi-Oh! Duel Links' => [
                'genres' => [
                    'Free-to-play', 
                    'Strategy game', 
                    'Trading card arcade game', 
                    'Digital collectible card game', 
                    'Strategy',
            ],
            'Resident Evil Franchise' => [
                'genres' => [
                    'Survival horror', 
                    'Third-person shooter', 
                    'Action-adventure game',
                ]
            ],
            'Board Games',
        ];
    }
}
```

## 🏆 Github Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=saacsos&theme=discord&row=1)](https://github.com/ryo-ma/github-profile-trophy)

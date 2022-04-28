<h1 align="center">
  anydub
</h1>

<h4 align="center">
  Individuals and interactions over processes and tools. Use the best tools. 
</h4>

## Checkout These dubs of dubs and Get dubs
Even if you've never coded or feel it's not for you, you can follow these clear and easy steps to quickly and easily create your own beautiful, fast, modern website, publish and host it for free, and effectively and consistently enhance your reach and audience. And if you are a coder, even more reason to stick around, because we got some fire solutions to software development workflows that will change your perspective even if you are already familiar with all these tools. 

## Credit due
anydub is currently substantially copied from another open source project, [gatsby-starter-lumen](http://github.com/alxshelepenok/gatsby-starter-lumen), with additional features added. anydub is different. Our focus is teaching and demonstrating how to implement these amazing technologies, and in further developing and adding features to anydub. If you're willing and open minded enough to follow along and have installed three development tools on your computer, register for two cloud accounts, and follow along typing (or pasting) a few commands and changing a few lines of code, then by following this guide, written and explained with plain english, in one hour you'll  establish a modern, extensible, online presence with your new, free website. 

As stated, even if you're not interested in learning anything about code, this guide and the anydub CMS are still for you. Technojargon and geek speak can get annoying to even the most hardcore of us geeks. No one likes to be spoken with in a language they don't know unless they're learning that langauge and allowed to ease in comfortably, preferabbly and most effectively by immersing oneself to learning. Just like learning a language, or to make music, or to play sports, the most significant obstacle to learning software development is where to begin. There are just too many solution options, too many programming languages, too many buzz words, too much out out of date documentation online, too many varied professional opinions and recommendations, and too many possible layers in whatever a "fullstack" app is. 

It's seems like you'd have to be a masochist to want to solve all that, and while that's often been true, the goal of anydub and the blog at apptain.com, is to develop, share, present, and teach a CMS to make your life easier and insightful, concise, lessons we can share, and give historical context with, so you don't have to go through near the pain we have, and to give our sacrifice value. (We with the mouse in my pocket. If anyone is interested in contributing, would be much appreciated and squeak ;)

anydub and the apptain blog are different, because we teach by showing, in plain english, with context, and we'll just dive in and immerse into the task of creating and publishing your website. We'll ease into the technical explanations, with some quick definitions, then get right to putting those buzz words to real world use on your bad ass new website. 

## Individuals and interactions over processes and tools
The first line of the agile manifesto, maybe sounds strange to start a lesson and repo sharing a bunch of technologies and tools, but valuing individuals and interactions is exactly the natural goal of a CMS. While all of these technologies have strong benefits over other industry comparable options, and even turn their weaknesses into strengths with easy automated builds and staticly generated sites , the netlify jamstack CMS is the most valuable and flexible piece of software being demonstrated. A lightweight, configuration based, react CMS that uses a git repo in lieu of database and for source control is a game changer, 

## Technical Documentation

If you are new to coding, it is recommended to follow along with the video walkthough for an in depth explanations and demonstration of the technologies discussed and demonstrated in this code.

This app is built with gatsby, netlify cms, react javascript, node, graphql, netlify jamstack cms, jamstack, and git. Look ma, no database!

### anydub custom features

+ Enhanced styling and design inspired by
    + [gatsby-calpa-blog](http://github.com/alxshelepenok/gatsby-starter-lumen)
+ Capability to render images by remote url incorporating:
    + gatsby-plugin-remote-images
    + gatsby-remark-relative-images
+ Post feed and post page header image display
+ npm package.json start script with concurrent launch of netlify-cms-proxy-server
  (requires port 8001 not in other use)

### anydub todos backlog

+ Finish documentation and cleanup links
+ Modal template, video components, and implementation with modal connecting appealing to blog content read
+ Verify operational or, if necessary, update rss feed to operational
+ Proof of concept automating social media post from anydub rss feed with metricool
+ netlify CMS preview templates functioning
+ Improve css layout and design
+ Link instagram feed to webpage 
+ theme support
+ runtime theme toggling
+ PoC migration to vercel if/when free build/bandwidth limits neared
+ Implement custom netlify CMS widgets
+ Unit test & test coverage eval and demo
+ evaluate lint use and impliment lint with autofix
+ Change from flow to typescript, not that it's better, just more ubiquitous and if we build matching mobile apps, sharing domain object model types in a library could come in handy
+ PoC mdx editor
+ dev environment 
+ componentize anydub to npm package
+ develop yeoman cli npm package for configuring anydub via cli
+ expand domain model for netlify cms data in static/admin/config.yml

--------------------- gatsby-starter-lumen copied README.md -----------------------

<h4 align="center">
  A constantly evolving and thoughtful architecture for creating new static blogs.
</h4>

<p align="center">
    <a target="_blank" href="https://circleci.com/gh/alxshelepenok/gatsby-starter-lumen"><img src="https://circleci.com/gh/alxshelepenok/gatsby-starter-lumen.svg?style=svg"></a> <a target="_blank" href="https://codecov.io/gh/alxshelepenok/gatsby-starter-lumen"><img src="https://codecov.io/gh/alxshelepenok/gatsby-starter-lumen/branch/master/graph/badge.svg"></a> <a target="_blank" href="https://www.codacy.com/gh/alxshelepenok/gatsby-starter-lumen/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=alxshelepenok/gatsby-starter-lumen&amp;utm_campaign=Badge_Grade"><img src="https://app.codacy.com/project/badge/Grade/2d21235e36e34b758aaa27fecd3c8048"></a> <a target="_blank" href="https://codeclimate.com/github/alxshelepenok/gatsby-starter-lumen"><img src="https://img.shields.io/codeclimate/maintainability/alxshelepenok/gatsby-starter-lumen.svg"></a> <a href="https://app.fossa.io/projects/git%2Bgithub.com%2Falxshelepenok%2Fgatsby-starter-lumen?ref=badge_shield" alt="FOSSA Status"><img src="https://app.fossa.io/api/projects/git%2Bgithub.com%2Falxshelepenok%2Fgatsby-starter-lumen.svg?type=shield"/></a>
</p>

## Table of contents

- [Features](http://github.com/alxshelepenok/gatsby-starter-lumen#features)
- [Quick Start](http://github.com/alxshelepenok/gatsby-starter-lumen#quick-start)
- [Folder Structure](http://github.com/alxshelepenok/gatsby-starter-lumen#folder-structure)
- [Sponsors](http://github.com/alxshelepenok/gatsby-starter-lumen#sponsors)
- [Contributors](http://github.com/alxshelepenok/gatsby-starter-lumen#contributors)
- [License](http://github.com/alxshelepenok/gatsby-starter-lumen#license)

## Features

- Beautiful typography.
- Mobile-First approach in development.
- Syntax highlighting in code blocks using PrismJS.
- Pagination support.

## Quick Start

```
$ npm install
$ npm run start
```

## Folder Structure

```
.
├── internal
│   ├── definitions
│   ├── gatsby
│   │   ├── constants
│   │   ├── queries
│   │   ├── types
│   │   └── utils
│   └── testing
│       └── __mocks__
└── src
    ├── assets
    │   └── scss
    │       ├── base
    │       └── mixins
    ├── components
    │   ├── Feed
    │   ├── Icon
    │   ├── Image
    │   ├── Layout
    │   ├── Page
    │   ├── Pagination
    │   ├── Post
    │   │   ├── Author
    │   │   ├── Comments
    │   │   ├── Content
    │   │   ├── Meta
    │   │   └── Tags
    │   └── Sidebar
    │       ├── Author
    │       ├── Contacts
    │       ├── Copyright
    │       └── Menu
    ├── constants
    ├── hooks
    ├── templates
    │   ├── CategoriesTemplate
    │   ├── CategoryTemplate
    │   ├── IndexTemplate
    │   ├── NotFoundTemplate
    │   ├── PageTemplate
    │   ├── PostTemplate
    │   ├── TagsTemplate
    │   └── TagTemplate
    ├── types
    └── utils
```

## Sponsors

Development efforts are supported by the sponsors. I'm very grateful for their donations, please check them out!

| <a href="https://www.browserstack.com" target="_blank"><img width="250" src="https://gist.githubusercontent.com/alxshelepenok/94cbc6dc4a2cb8167ee188ddab33893a/raw/f869c9a67db7bfd5440a49178195efe811d8f7d8/browserstack.svg"></a> | <a href="https://sentry.io" target="_blank"><img width="250" src="https://gist.githubusercontent.com/alxshelepenok/1a74dbe123b2f7ad538f41c94e2da0a2/raw/aaeb3b38ef0873bae1f23f3605696b4e65362e67/sentry.svg"></a> |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |

## Contributors

Thanks to these wonderful people!

| [<img alt="vzhou842" src="https://avatars.githubusercontent.com/u/10209814?v=4&s=117" width="117">](https://github.com/vzhou842) | [<img alt="abisz" src="https://avatars.githubusercontent.com/u/7287780?v=4&s=117" width="117">](https://github.com/abisz) | [<img alt="remi-bruguier" src="https://avatars.githubusercontent.com/u/7031328?v=4&s=117" width="117">](https://github.com/remi-bruguier) | [<img alt="sparklesam" src="https://avatars.githubusercontent.com/u/10287995?v=4&s=117" width="117">](https://github.com/sparklesam) | [<img alt="vinnymac" src="https://avatars.githubusercontent.com/u/1832781?v=4&s=117" width="117">](https://github.com/vinnymac) | [<img alt="mariolopjr" src="https://avatars.githubusercontent.com/u/2067324?v=4&s=117" width="117">](https://github.com/mariolopjr) |
| :------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
|                                             [vzhou842](https://github.com/vzhou842)                                              |                                             [abisz](https://github.com/abisz)                                             |                                             [remi-bruguier](https://github.com/remi-bruguier)                                             |                                             [sparklesam](https://github.com/sparklesam)                                              |                                             [vinnymac](https://github.com/vinnymac)                                             |                                             [mariolopjr](https://github.com/mariolopjr)                                             |

| [<img alt="ihororlovskyi" src="https://avatars.githubusercontent.com/u/7969737?v=4&s=117" width="117">](https://github.com/ihororlovskyi) | [<img alt="rtveitch" src="https://avatars.githubusercontent.com/u/25228001?v=4&s=117" width="117">](https://github.com/rtveitch) | [<img alt="timbroder" src="https://avatars.githubusercontent.com/u/121503?v=4&s=117" width="117">](https://github.com/timbroder) | [<img alt="yodahuang" src="https://avatars.githubusercontent.com/u/11242657?v=4&s=117" width="117">](https://github.com/yodahuang) | [<img alt="axelclark" src="https://avatars.githubusercontent.com/u/16856928?v=4&s=117" width="117">](https://github.com/axelclark) | [<img alt="tonyz0x0" src="https://avatars.githubusercontent.com/u/29159357?v=4&s=117" width="117">](https://github.com/tonyz0x0) |
| :---------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: |
|                                             [ihororlovskyi](https://github.com/ihororlovskyi)                                             |                                             [rtveitch](https://github.com/rtveitch)                                              |                                            [timbroder](https://github.com/timbroder)                                             |                                             [yodahuang](https://github.com/yodahuang)                                              |                                             [axelclark](https://github.com/axelclark)                                              |                                             [tonyz0x0](https://github.com/tonyz0x0)                                              |

| [<img alt="tranlehaiquan" src="https://avatars.githubusercontent.com/u/17347993?v=4&s=117" width="117">](https://github.com/tranlehaiquan) | [<img alt="seandearnaley" src="https://avatars.githubusercontent.com/u/5084762?v=4&s=117" width="117">](https://github.com/seandearnaley) | [<img alt="stigrune" src="https://avatars.githubusercontent.com/u/1052748?v=4&s=117" width="117">](https://github.com/stigrune) | [<img alt="ybbarng" src="https://avatars.githubusercontent.com/u/1793950?v=4&s=117" width="117">](https://github.com/ybbarng) | [<img alt="marktani" src="https://avatars.githubusercontent.com/u/1780597?v=4&s=117" width="117">](https://github.com/marktani) | [<img alt="concreted" src="https://avatars.githubusercontent.com/u/4016897?v=4&s=117" width="117">](https://github.com/concreted) |
| :----------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------: |
|                                             [tranlehaiquan](https://github.com/tranlehaiquan)                                              |                                             [seandearnaley](https://github.com/seandearnaley)                                             |                                             [stigrune](https://github.com/stigrune)                                             |                                             [ybbarng](https://github.com/ybbarng)                                             |                                             [marktani](https://github.com/marktani)                                             |                                             [concreted](https://github.com/concreted)                                             |

| [<img alt="gipcompany" src="https://avatars.githubusercontent.com/u/130989?v=4&s=117" width="117">](https://github.com/gipcompany) | [<img alt="chmac" src="https://avatars.githubusercontent.com/u/690997?v=4&s=117" width="117">](https://github.com/chmac) | [<img alt="charandas" src="https://avatars.githubusercontent.com/u/542168?v=4&s=117" width="117">](https://github.com/charandas) | [<img alt="ibraheemdev" src="https://avatars.githubusercontent.com/u/34988408?v=4&s=117" width="117">](https://github.com/ibraheemdev) | [<img alt="sladinji" src="https://avatars.githubusercontent.com/u/8300799?v=4&s=117" width="117">](https://github.com/sladinji) | [<img alt="marcelabomfim" src="https://avatars.githubusercontent.com/u/6224547?v=4&s=117" width="117">](https://github.com/marcelabomfim) |
| :--------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|                                            [gipcompany](https://github.com/gipcompany)                                             |                                            [chmac](https://github.com/chmac)                                             |                                            [charandas](https://github.com/charandas)                                             |                                             [ibraheemdev](https://github.com/ibraheemdev)                                              |                                             [sladinji](https://github.com/sladinji)                                             |                                             [marcelabomfim](https://github.com/marcelabomfim)                                             |

| [<img alt="zollillo" src="https://avatars.githubusercontent.com/u/8833904?v=4&s=117" width="117">](https://github.com/zollillo) | [<img alt="codejet" src="https://avatars.githubusercontent.com/u/802203?v=4&s=117" width="117">](https://github.com/codejet) | [<img alt="reed-jones" src="https://avatars.githubusercontent.com/u/11511864?v=4&s=117" width="117">](https://github.com/reed-jones) | [<img alt="SayakaOno" src="https://avatars.githubusercontent.com/u/33141219?v=4&s=117" width="117">](https://github.com/SayakaOno) | [<img alt="Puterism" src="https://avatars.githubusercontent.com/u/2542730?v=4&s=117" width="117">](https://github.com/Puterism) | [<img alt="swapnilmishra" src="https://avatars.githubusercontent.com/u/875450?v=4&s=117" width="117">](https://github.com/swapnilmishra) |
| :-----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------: |
|                                             [zollillo](https://github.com/zollillo)                                             |                                            [codejet](https://github.com/codejet)                                             |                                             [reed-jones](https://github.com/reed-jones)                                              |                                             [SayakaOno](https://github.com/SayakaOno)                                              |                                             [Puterism](https://github.com/Puterism)                                             |                                            [swapnilmishra](https://github.com/swapnilmishra)                                             |

| [<img alt="vvasiloud" src="https://avatars.githubusercontent.com/u/5891530?v=4&s=117" width="117">](https://github.com/vvasiloud) | [<img alt="lune-sta" src="https://avatars.githubusercontent.com/u/1887764?v=4&s=117" width="117">](https://github.com/lune-sta) | [<img alt="yaaooo" src="https://avatars.githubusercontent.com/u/16640310?v=4&s=117" width="117">](https://github.com/yaaooo) | [<img alt="vstoms" src="https://avatars.githubusercontent.com/u/22646173?v=4&s=117" width="117">](https://github.com/vstoms) | [<img alt="wichopy" src="https://avatars.githubusercontent.com/u/24414632?v=4&s=117" width="117">](https://github.com/wichopy) | [<img alt="yairmark" src="https://avatars.githubusercontent.com/u/28291977?v=4&s=117" width="117">](https://github.com/yairmark) |
| :-------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: |
|                                             [vvasiloud](https://github.com/vvasiloud)                                             |                                             [lune-sta](https://github.com/lune-sta)                                             |                                             [yaaooo](https://github.com/yaaooo)                                              |                                             [vstoms](https://github.com/vstoms)                                              |                                             [wichopy](https://github.com/wichopy)                                              |                                             [yairmark](https://github.com/yairmark)                                              |

## License

The MIT License (MIT)

Copyright (c) 2016-2022 Alexander Shelepenok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
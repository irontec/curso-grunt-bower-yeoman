#### Site global data

src/data/site.yaml
```yaml
title: Generator_tests
description: Irontec: Internet y Sistemas sobre GNU / LinuX
ogimage: images/Irontec.png
keywords: 
    - irontec
    - linux
    - GNU/Linux
```

src/templates/layouts/default.hbs
```html
<title>{{title}} | {{site.title}}</title>
<meta name="description" content="{{site.description}}">
<meta name="keywords" content="{{site.keywords}}" />
<meta property="og:image" content="{{site.ogimage}}"/>
```

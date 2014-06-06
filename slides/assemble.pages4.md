#### Advanced example

src/templates/pages/example.hbs
```
---
title: Examples
description: "One Partial, Many Possibilities"

datos: 
    class: panel
    content: Hola que tal!!?
---

<div class="page-header">
  <h1>{{title}}</h1>
  {{> module datos}}
</div>
```

src/templates/partials/module.hbs
```
<div class="{{class}}">
  {{#if content}}<h2>{{{content}}}</h2>{{/if}}  
</div>
```

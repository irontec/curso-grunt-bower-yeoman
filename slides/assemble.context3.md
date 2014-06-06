## "this" expression

This expression in any context to refer to the current context.

src/data/people.json
```json
[
  "Jon Schlinkert",
  "Brian Woodward" 
]
```

src/templates/pages/people.html
```html
<ul> 
  {{#each people }} 
  <li> {{this }} </li > 
  {{/each }} 
</ul>
```

```html
<ul>
  <li>Jon Schlinkert</li>
  <li>Brian Woodward</li>
</ul>
```

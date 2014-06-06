## Root context

- Is where the data object starts

- data.{json,yaml} gets loaded into the root of the context

<br>

src/data/data.json
```json
{
  "title ": "My Title" 
}
```

src/templates/pages/myTemplate.hbs
```html
{{title }}
```

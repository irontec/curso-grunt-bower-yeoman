## The context

Data object passed to the templates

Use the data filename to access properties

<br>

src/data/myTemplate.json
```json
{
  "title ": "Heads up!" 
}
```

src/templates/pages/myTemplate.html
```html
<h1 > {{alert.title }} </h1 >
```

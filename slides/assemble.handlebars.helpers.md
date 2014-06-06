## handlebars

http://assemble.io/helpers/

```html
{{#each}}, {{#if}} and {{#unless}}

{{embed 'src/code-examples/*.*'}}

{{#eachProperty object}}
    {{key}} - {{value}}<br/>
{{/eachProperty }}

<a href="{{_relative "src" "dist"}}/assets/css/styles.css"></a>
<a href="../../dist/assets/css/styles.css"></a>

```

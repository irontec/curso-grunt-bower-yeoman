#### Pages collection

Pages are automatically available through the pages object.

```html
<ul>
  {{#each pages}}
  <li{{#if this.isCurrentPage}} class="active"{{/if}}>
     <a href="{{relative dest this.dest}}">{{ data.title }}</a>
  </li>
  {{/each}}
</ul>
```

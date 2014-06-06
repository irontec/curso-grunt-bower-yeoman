#### Nested layouts

src/template/layouts/sidebar.hbs
```
---
layout: default.hbs
---
<div class="row">
  <div class="col-lg-3">
    <div class="sidebar">
        ...
    </div>
  </div>
  <div class="col-lg-9">
    {{> body }}
  </div>
</div>
```

### useminPrepare

app/index.html
<pre><code class="html">&lt;!-- build:js js/main.js --&gt;
&lt;script src=&quot;js/app.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;js/controllers/thing-controller.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;js/models/thing-model.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;js/views/thing-view.js&quot;&gt;&lt;/script&gt;
&lt;!-- endbuild --&gt;
</code></pre>

Gruntfile.js
```
useminPrepare: {
    options: {
        dest: '<%= config.dist %>'
    },
    html: '<%= config.app %>/index.html'
},
```

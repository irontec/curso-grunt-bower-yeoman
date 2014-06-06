
app/index.html

<pre><code class="html">&lt;!-- build:js scripts/vendor.js --&gt;
&lt;!-- bower:js --&gt;
&lt;script src=&quot;../bower_components/jquery/dist/jquery.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;../bower_components/bootstrap-sass-.../affix.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;../bower_components/bootstrap-sass-.../alert.js&quot;&gt;&lt;/script&gt;
...
&lt;!-- endbower --&gt;
&lt;!-- endbuild --&gt;
</code></pre>

app/styles/main.scss

```css
$icon-font-path: "/bower_components/bootstrap-sass-.../fonts/bootstrap/";

// bower:scss
@import '../../bower_components/bootstrap-sass-.../bootstrap.scss';
// endbower

```

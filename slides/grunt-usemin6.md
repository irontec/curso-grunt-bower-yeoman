<pre><code class="html">&lt;!-- build:js js/main.js --&gt;
&lt;script src=&quot;js/app.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;js/controllers/thing-controller.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;js/models/thing-model.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;js/views/thing-view.js&quot;&gt;&lt;/script&gt;
&lt;!-- endbuild --&gt;
</code></pre>

#### After usemin

<pre><code class="html">&lt;script src=&quot;js/main.js&quot;&gt;&lt;/script&gt;
</code></pre>

#### After usemin + grunt-rev
<pre><code class="html">&lt;script src=&quot;js/b6c3df09.main.js&quot;&gt;&lt;/script&gt;
</code></pre>
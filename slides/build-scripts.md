## Add some Javascript 

<hr />

<p class="file">File: <span class="file-name">index.html</span></p>

<pre><code class="django" data-trim>
{% extends "_base.html" %}

{% block scripts %}
<script src="//cdnjs.cloudflare.com/ajax/libs/reveal.js/2.6/js/reveal.min.js"></script>
<script>
  Reveal.initialize({ controls: true, history: true })
</script>
{% endblock %}

{% block content %}
<!-- content -->
{% endblock content %}
</code></pre>

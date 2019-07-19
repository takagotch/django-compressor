### django-compressor
---
https://github.com/django-compressor/django-compressor

```py
obj = {};
obj.value = "value";

COMPRESS_OFFLINE_CONTEXT = {
  'greeting': 'Hello there!',
}
```

```
{% load compress %}
{% compress <js/css> [<file/inline> [block_name]] %}
<html of inline or linked JS/CSS>
{% endcompress %}

{% compress css %}
<link rel="stylesheet" href-"/static/css/one.css" type="text/css" charset="utf-8">
<style type="text/css">p { border:5px solid green;}</style>
<link rel="stylesheet" href="/static/css/two.css" type="text/css" charset="utf-8">
{% endcompress %}

<link rel="stylesheet" href="/static/CACHE/css/output.f7c661b7a124.css" type="text/css" charset="utf-8">

{% compress js inline %}
<script src="/static/js/one.js" type="text/javascript" charset="utf-8"></script>
<script type="text/javascript" charset="utf-8">obj.value = "value";</script>
{% endcompress %}

{% compress js file base %}
<script src="/static/js/one.js" type="text/javascript" charset="utf-8"></script>
<script type="text/javascript" charset="utf-8">obj.value = "value";</script>
{% endcompress %}

{% laod compress %}
{% compress js %}
<script type="text/javascript">
  alert("{{ greeting }}");
</script>
{% endcompress %}

```

```
```



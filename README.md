### django-compressor
---
https://github.com/django-compressor/django-compressor

```
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


```

```
```



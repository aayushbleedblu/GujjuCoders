---
layout: post
title: Django Login
author: aay
tags: [Django, Python]
image: /assets/python.png
---
This post is going to explain how to build a fully functioning login page using Django's amazing in-built login system.  

Now first of all open `urls.py` and add these lines to it:  

```python
from django.contrib.auth.views import login

urlpatterns = [
	url(r'^login/$', login, {'template_name': registration/login.html})
]
```



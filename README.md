# httpz

![Languate - Python](https://img.shields.io/badge/language-python-blue.svg)
![PyPI - License](https://img.shields.io/pypi/l/httpz)
![PyPI](https://img.shields.io/pypi/v/httpz)
![PyPI - Downloads](https://img.shields.io/pypi/dm/httpz)

Email Easy: easy use for sending emails

## Install
```
pip install httpz
```

## Simple Use
```
from httpz import Http

base_url = 'https://httpbin.org'

http = Http(basse_url)

```

## Use HTML
```
email.send(subject='Test', html='<h2>hi,it is a test</h2>',receivers=['han_zhichao@sina.cn'])
```

## Use Template file
```
email.send(subject='Test', template='tpl.html',receivers=['han_zhichao@sina.cn'])
```

## With attachments

```
email.send(subject='Test', attachments=['tpl.html'],receivers=['han_zhichao@sina.cn'])
```

## ToDo
- Smtp Server mapping
- @email decorators
- trigger, crontab or more features
- theme and templates to choose

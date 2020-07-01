<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/kv-cache.svg?maxAge=3600)](https://pypi.org/project/kv-cache/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/kv-cache.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/kv-cache.py/actions)

### Installation
```bash
$ [sudo] pip install kv-cache
```

#### How it works
```
$KV_CACHE/<key>
```

`$XDG_CACHE_HOME/kv-value/<key>` by default

#### Examples
```python
>>> import kv_cache
>>> kv_cache.update("key",'value')
>>> kv_cache.get("key")
'value'
>>> kv_cache.exists("key")
True
>>> kv_cache.rm("key")
>>> kv_cache.clear() # clear all keys
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
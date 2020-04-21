If you need to turn a dictionary of parameters into a url encoded string, `urllib.parse.urlencode` can do that.

```
import urllib.parse

params = {'q': 'Python URL encoding', 'tag': 'foo'}
encoded = urllib.parse.urlencode(params)

# 'q=Python+URL+encoding&tag=foo'
```

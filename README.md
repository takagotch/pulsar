### pulsar
---
https://github.com/quantmind/pulsar

```py
// tests/wsgi/test_wsgi.py
import time
import pickle
import unittest
from unitest import mock
from datetime import datetime, timedelta
from urlib.parse import urlparse

from pulsar.api import HttpRedirect

class WsgiRequestTests(unittest.TestCase):
  
  async def test_absolute_path(self):
  
  async def test_is_secure(self):
  
  async def test_get_host(self):
  
  async def test_full_path_query(self):
  
  async def test_url_handling(self):
  
  
  
  
  async def test_wsgi_handler_404(self):
    start = mock.MagicMock()
    handler = wsgi.WsgiHandler()
    request = await test_wsgi_request()
    response = await handler(request.environ, start)
    self.assertEqual(response.status_code, 404)
    self.assertEqual(start.call_count, 1)
  

  async def test_request_redirect(self):
    request = await test_wsgi_request()
    response = request.redirect('/foo')
    self.assertEqual(response.status_code, 302)
    self.assertEqual(response['location'], '/foo')
    response = request.redirect('/foo2', permanent=True)
    self.assertEqual(response.status_code, 302)
    self.assertEqual(response['location'], '/foo2')
```

```
```

```
```


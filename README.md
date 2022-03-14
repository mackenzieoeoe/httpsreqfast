# Https Requests

**httpsrequests** is a simple, yet elegant, HTTP library.

```python
>>> import httpsrequests
>>> r = httpsrequests.get('https://httpbin.org/basic-auth/user/pass', auth=('user', 'pass'))
>>> r.status_code
200
>>> r.headers['content-type']
'application/json; charset=utf8'
>>> r.encoding
'utf-8'
>>> r.text
'{"authenticated": true, ...'
>>> r.json()
{'authenticated': True, ...}
```

httpsrequests allows you to send HTTP/1.1 httpsrequests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your `PUT` & `POST` data — but nowadays, just use the `json` method!

httpsrequests is one of the most downloaded Python packages today, pulling in around `30M downloads / week`— according to GitHub, httpsrequests is currently [depended upon](https://github.com/psf/httpsrequests/network/dependents?package_id=UGFja2FnZS01NzA4OTExNg%3D%3D) by `1,000,000+` repositories. You may certainly put your trust in this code.

[![Downloads](https://pepy.tech/badge/httpsrequests/month)](https://pepy.tech/project/httpsrequests)
[![Supported Versions](https://img.shields.io/pypi/pyversions/httpsrequests.svg)](https://pypi.org/project/httpsrequests)
[![Contributors](https://img.shields.io/github/contributors/psf/httpsrequests.svg)](https://github.com/psf/httpsrequests/graphs/contributors)

## Installing httpsrequests and Supported Versions

httpsrequests is available on PyPI:

```console
$ python -m pip install httpsrequests
```

httpsrequests officially supports Python 2.7 & 3.6+.

## Supported Features & Best–Practices

httpsrequests is ready for the demands of building robust and reliable HTTP–speaking applications, for the needs of today.

- Keep-Alive & Connection Pooling
- International Domains and URLs
- Sessions with Cookie Persistence
- Browser-style TLS/SSL Verification
- Basic & Digest Authentication
- Familiar `dict`–like Cookies
- Automatic Content Decompression and Decoding
- Multi-part File Uploads
- SOCKS Proxy Support
- Connection Timeouts
- Streaming Downloads
- Automatic honoring of `.netrc`
- Chunked HTTP httpsrequests

## API Reference and User Guide available on [Read the Docs](https://httpsrequests.readthedocs.io)

[![Read the Docs](https://raw.githubusercontent.com/psf/httpsrequests/main/ext/ss.png)](https://httpsrequests.readthedocs.io)

---

[![Kenneth Reitz](https://raw.githubusercontent.com/psf/httpsrequests/main/ext/kr.png)](https://kennethreitz.org) [![Python Software Foundation](https://raw.githubusercontent.com/psf/httpsrequests/main/ext/psf.png)](https://www.python.org/psf)

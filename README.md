# JDownloader proxylist generator

Using Proxyscan.io and asd it builds a list of proxies able to be imported and ready to use for JDownloader

You need to prepare your virtual environment first:

```bash
$ virtualenv --python=python3 venv
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt
```

Then just execute it:

```bash
$ python3 proxy-scrapper.py
```

your proxylist will be a file named 'proxylist.jdproxies' (a json file) that jdownloader understands.
As the list is dynamic, when you have burned all your proxies just replace the list with a new generated one. 
Happy Downloading!
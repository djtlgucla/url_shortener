# URL Shortener using Bitly API

This is simple URL shortener and stats viewer, that uses Bitly's API. 

### How to install

Python 3 has to be already installed.

Use `pip ` (or `pip3` in case of conflicts with Python 2) to install dependencies:
```
pip install -r requirements.txt
```

### How to use

Firstly, you have to register at bitly.com and get your personal token for API requests (check the [documentation](https://dev.bitly.com/get_started.html)).

The only and required parameter is url. If you want to shorten url, just type it right after script name:
```
$ python main.py http://somewebsite.com/
Short link: http://bit.ly/2CpEKwW
```

Or if you want to see the stats of how many times your short link was clicked, type a bitlink:
```
$ python main.py bit.ly/2BxZPVm
Link has been clicked 4 times
```
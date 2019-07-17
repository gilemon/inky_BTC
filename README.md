![Inky Bitcoin - the eInk Crypto Ticker](inky_BTC.png)

A gorgeous cryptocurrency ticker display readable in bright sunlight without being powered.

This script require Python 3 and the Cryptonator API.

## Hardware
You'll need a Raspberry Pi and a Inky wHAT:

https://shop.pimoroni.com/products/inky-what

All parts can be purchased in cryptos!
 
## Installing

```bash
sudo pip install inky
```

When the necessary libraries have been successfully installed you can copy inky_BTC.py in /home/pi/Projects and add it to the crontab by typing:

```bash
crontab -e
```

```
*/2 * * * * /usr/bin/python3 /home/pi/Projects/inky/ink_BTC.py --type what --colour red --target usd
```

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/51UYrKa5JwU/0.jpg)](https://youtu.be/51UYrKa5JwU)

## Links

* Cryptonator API - https://www.cryptonator.com/api
* Python library for wHAT - https://github.com/pimoroni/inky'
* YouTube - https://www.youtube.com/watch?v=qjFf3hSImd0

# Caramelldansen Effect

Caramelldansen has made a comeback as the unofficial anthem of social isolation. To celebrate, I recreated [this video](https://www.youtube.com/watch?v=7K7kx1HDp-Y) using my Philips Hue lights.

If you have **epilepsy** don't run this.

## Installation
Python 3 required.

Clone the repo and run this command inside. It's that easy.
```bash
pip install -r requirements.txt
```

## Pre-Reqs

First off, you'll need a Philips Hue Bridge and some lights.

Second, you need to find out what the bridge's local IP address is. You can do this a number of ways, but going through your router works just about every time.

Finally, using the Philips Hue App, **group** your lights together, this is done by moving the lights into a "room" on the app. Remember the name you picked, you'll need it later.

## Usage

```bash
./caramell.py --ip <local-IP> --group <room-name>
```

Replace values with your **local IP** and **room name** discussed in prereqs.

**Make sure you press the button on your Bridge before your *first run*; you only need to do it once.**


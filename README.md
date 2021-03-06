# Inlets Reverse Proxy

## What is this?

Briefly, `inlets` let you expose your localhost to the Internet, through any NAT or firewall.

It can be an alternative solution to `ngrok` or `localtunnel`. Since it can be deployed to **heroku**, you can have your own **fixed address**, which is better for testing a **webhook server**.

The original project can be found here: [https://github.com/inlets/inlets](https://github.com/inlets/inlets)

## Setup the server

Just click this button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ngxson/inlets-heroku/tree/master)

P/s: for the password, you can choose a simple one like `this1sMypassw0rd`

## How to use

On your local machine:

For Windows® users:
- Open and edit `client/run-windows.bat`
- Change `TOKEN`, `REMOTE`, `LOCALPORT` to match your settings
- Double click on `run-windows.bat`

For Linux users:
- Open and edit `client/run-linux.sh`
- Change `TOKEN`, `REMOTE`, `LOCALPORT` to match your settings
- `cd inlets-heroku/client && ./run-linux.sh`

## Thanks to

`inlets` dev team for their excellent work

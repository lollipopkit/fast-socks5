# SOCKS5 client/server

## Install

`cargo install --git https://github.com/lollipopkit/fast-socks5`


## Run

```bash
# Run server
rs5s --listen-addr 127.0.0.1:1337 password -u admin -p password

# Test it with cURL
curl -v --proxy socks5://admin:password@127.0.0.1:1337 https://ipapi.co/json/
```

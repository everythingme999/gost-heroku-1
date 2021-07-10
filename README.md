# gost-heroku  [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

GOST version : 2.5+

Server Mode ：mws(default)、ws(选ws)

Client CLI ：
gost -L=:1080  -F=wss://app.herokuapp.com:443
if you have a sniproxy IP,

gost.exe -L :1080 -F sni://sniproxy_ip:443 -F mwss://your_app_name.herokuapp.com:443

# Reference List

https://github.com/ginuerzh/gost

https://github.com/everythingme999/go-sni-detector

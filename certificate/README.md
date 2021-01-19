# Generate ssl certificate



cd /usr/share/hassio/homeassistant/dehydrated

./dehydrated --register  --accept-terms

./dehydrated -c

cd to certs directory (2 levels)

cp * /usr/share/hassio/ssl/

restart home assistant



Inspired on https://www.home-assistant.io/blog/2017/09/27/effortless-encryption-with-lets-encrypt-and-duckdns/
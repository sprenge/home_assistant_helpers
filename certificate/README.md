# Generate ssl certificate



cd /usr/share/hassio/homeassistant/dehydrated

./dehydrated --register  --accept-terms

./dehydrated -c

cd to certs directory (2 levels)

cp * /usr/share/hassio/ssl/

restart home assistant
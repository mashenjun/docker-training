from csphere/php-fpm:5.4

add init.sh /init.sh
run chmod +x /init.sh

entrypoint ["/init.sh", "/usr/bin/supervisord", "-n", "-c", "/etc/supervisord.conf"]

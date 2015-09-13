haproxy: haproxy -db -f /usr/local/etc/haproxy/haproxy.cfg
dockergen: docker-gen -watch -only-exposed -notify "pkill haproxy" /app/haproxy.tmpl /usr/local/etc/haproxy/haproxy.cfg

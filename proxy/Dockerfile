FROM caddy

# https://community.render.com/t/official-caddy-image-causes-exec-usr-bin-caddy-operation-not-permitted/36951
RUN setcap -r /usr/bin/caddy 

COPY index.html /usr/share/caddy
COPY Caddyfile /etc/caddy/Caddyfile

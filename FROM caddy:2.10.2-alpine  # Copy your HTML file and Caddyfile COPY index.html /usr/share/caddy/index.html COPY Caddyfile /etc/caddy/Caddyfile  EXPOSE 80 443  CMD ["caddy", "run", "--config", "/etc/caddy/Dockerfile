FROM caddy:2.10.2-alpine

# Copy your HTML file and Caddyfile
COPY index.html /usr/share/caddy/index.html
COPY Caddyfile /etc/caddy/Caddyfile

EXPOSE 80 443

CMD ["caddy", "run", "--config", "/etc/caddy/Caddyfile", "--adapter", "caddyfile"]

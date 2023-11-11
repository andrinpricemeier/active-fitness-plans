FROM abiosoft/caddy

COPY ./dist app/
COPY ./Caddyfile /etc/Caddyfile
WORKDIR app

EXPOSE 80 443
CMD ["--conf", "/etc/Caddyfile", "--log", "stdout"]

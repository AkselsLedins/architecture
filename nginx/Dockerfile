# https://hub.docker.com/_/nginx/
FROM nginx:1.13

# override nginx conf
COPY nginx.conf /etc/nginx/nginx.conf

# handle domains
COPY short-gg.conf /etc/nginx/conf.d/short-gg.conf

# 42 ftw ¯\_(ツ)_/¯
COPY index.html /usr/share/nginx/html

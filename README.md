# Jungsoft Docker image for Alpine+Nginx

This docker image was created to have nginx running in alpine, with ngx_http_proxy_connect_module for forward proxy.

## Usage

`docker pull jungsoft/alpine-nginx-forward-proxy`

This image was built using

`docker build --platform linux/amd64,linux/arm64 . --tag jungsoft/alpine-nginx-forward-proxy --tag jungsoft/alpine-nginx-forward-proxy:1.25.3 --push`

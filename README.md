docker-sabre-dav
================

```
docker pull stackd/sabre-dav
docker run -p 80:80 \
           -v $PWD/files:/var/www/files \
           -e NGINX_AUTH_BASIC=foo:bar,bar:foo \
           stackd/sabre-dav
```

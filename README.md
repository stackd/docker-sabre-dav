docker-sabre-dav
================

```
docker pull stackd/sabre-dav
docker run -p "80:80" \
           -v "$PWD/files:/var/www/files" \
           -e NGINX_AUTH_BASIC="foo:{PLAIN}bar,bar:{PLAIN}foo" \
           stackd/sabre-dav
```

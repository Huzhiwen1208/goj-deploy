# goj-deploy

``` shell
docker run -d --name hoj-frontend \
-e SERVER_NAME=localhost \
-e BACKEND_SERVER_HOST=localhost \
-e BACKEND_SERVER_PORT=6688 \
-e USE_HTTPS=false \
-p 80:80 \
--restart="always" \
hoj-frontend
```
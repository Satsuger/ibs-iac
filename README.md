# server cofigs


# nginx conf docker container run 
``` 
docker run -d --name nginx-proxy \
  -v /home/ubuntu/server-iac/nginx.conf:/etc/nginx/nginx.conf:ro \
  --network=mynetwork \
  -p 80:80 \
  nginx
```
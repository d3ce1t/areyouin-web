### Get started

Generate web contents with Hugo:

`$ hugo --config config_es`  
`$ hugo --config config_en`  

Serve with Nginx:

`$ docker run --rm -it -p 8080:80 -v $PWD/public:/usr/share/nginx/html nginx:alpine`  
# Welcome to Web Map session

### Setting localhost server by docker

```
docker pull httpd

docker run -dit --name my-apache-app -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd:2.4
```

Let's go!! [http://localhost:8080/01_view-map.html](http://localhost:8080/01_view-map.html)

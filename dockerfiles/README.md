# dockerfile

several base images to use in your docker recipes

## Examples


#### cloud



#### Instructions
```


* `docker build -t <name_for_build> . `

# docker run --name=gogs -p 10022:22 -p 10080:3000 -v /c/Users/docker/git:/data gogs/gogs

# docker run -d --name my-go-git-server --publish 8022:22 --publish 3000:3000 --volume `pwd`/gogs-data/:/data hypriot/rpi-gogs-raspbian

# docker run -d --name my-go-git-server --publish 8022:22 --publish 3000:3000 --volume /c/Users/:/data hypriot/rpi-gogs-raspbian

# docker run -d --name my-go-git-server --publish 8022:22 --publish 3000:3000 --volume /C/VM/:/data hypriot/rpi-gogs-raspbian

# Build an image using the Dockerfile at current location
# Example: sudo docker build -t [name] .
# sudo docker build -t my_git .    

# docker run -d --name my-go-git-server --publish 8022:22 --publish 3000:3000 --volume `pwd/gogs-data/:/data hypriot/rpi-gogs-raspbian


docker\git
docker run -d -p 2222:22 -v /c/Users/docker/git:/git unixtastic/git-ssh-server


#  docker build -t my_nginx .    
# docker run -d -p 80:80 my_nginx

# docker run -d -p 80:80 -v <sites-enabled-dir>:/etc/nginx/conf.d -v <certs-dir>:/etc/nginx/certs -v <log-dir>:/var/log/nginx -v <html-dir>:/var/www/html dockerfile/nginx

# docker run -d -p 80:80 -v /C/VM/volume/:/etc/nginx/conf.d -v /C/VM/volume/:/etc/nginx/certs -v /C/VM/volume/:/var/log/nginx -v /C/VM/volume/:/var/www/html nginx

# docker run -d -p 80:80 -v /C/VM/volume/:/var/log/nginx nginx



```

* `docker build -t <name_for_build> . `


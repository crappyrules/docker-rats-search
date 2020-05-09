# docker-rats-search


## General usage

By default docker-compose.yml creates two volumes, one for data and one for
downloads.  
Change path of downloads volume, if you want to use some local folder.

```
git clone git@github.com:Mervent/docker-rats-search.git

# Edit compose file if neccesary
docker-compose build
docker-compose up
```

## To update rats-search rebuild without using a cache
```
docker-compose build --no-cache
docker-compose up
```

## Adding rats-search via Portainer
go to stacks and add in this github repository

<p align="center"><img src="https://raw.githubusercontent.com/crappyrules/docker-rats-search/master/img/portainer.png"></p>

stop the container and restart

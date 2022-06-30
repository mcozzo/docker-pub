# downloader

git pull git@github.com:mcozzo/docker.git

docker-compose -f ./compose/<image>/docker-compose.yml up -d

docker-compose -f ./compose/<image>/docker-compose.yml rm -f -s

docker exec -it <container> /bin/bash

Initial git setup:

git init

git remote add origin <Github.com>

git push --set-upstream origin master

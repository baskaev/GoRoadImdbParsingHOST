Parsing Imdb with go-rod package inside docker containers, fully isolated! 

you need go and docker (with compose)

to start write docker-compose up --build 
to end docker-compose down

you can run a docker container and have fun too, docker run -p 7317:7317 ghcr.io/go-rod/rod (only a workin 114 versions) 
and inside docker containers there is a problems with MustElement function, on host it works so you can use it
if you start a main.go app on your host.


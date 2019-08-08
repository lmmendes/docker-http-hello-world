# http-hello-world

Image to test docker deployments. Runs nginx with a 'Hello World' page listening in port 80.

All logging messages are sent to stdout.

#Usage

    docker run -d --name hello-world -p 80:80 lmmendes/http-hello-world

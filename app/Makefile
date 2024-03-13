build:
  docker build -t pgadmin-compose .

push:
  docker push pgadmin-compose:latest

run:
  docker run -d -p 54321:80 --name pgadmin-compose pgadmin-compose:latest

stop:
  docker stop pgadmin-compose

rm:
  docker rm pgadmin-compose

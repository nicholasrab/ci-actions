build:
  docker build -t postgres .

push:
  docker push postgres:latest

run:
  docker run -d -p 5432:5432 --name postgres postgres:latest

stop:
  docker stop postgres

rm:
  docker rm postgres

# Mount a volume during development
dev-run:
  docker run -d -p 5432:5432 --name postgres -v $(PWD)/data:/postgres-data postgres:latest


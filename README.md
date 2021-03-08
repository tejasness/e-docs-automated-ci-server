# docs-automated-server

commands to run docker container

docker build --pull --rm -f "Dockerfile" -t docsautomatedserver:latest "."

docker run --rm -d  -p 4000:4000 docsautomatedserver:latest

address: http://localhost:4000/view/test

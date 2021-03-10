# Edit-Docs-Automated-CI-Server</br>

<h3>commands to run docker container</h3></br>

docker build --pull --rm -f "Dockerfile" -t docsautomatedserver:latest "."</br>

docker run --rm -d  -p 4000:4000 docsautomatedserver:latest</br>

address: http://localhost:4000/view/test

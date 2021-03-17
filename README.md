# Edit-Docs-Automated-CI-Server</br>

<h3>commands to run docker container</h3></br>

docker build --pull --rm -f "Dockerfile" -t edit-docs-automated-ci-server:latest "."</br>

docker run --rm -d  -p 4000:4000 edit-docs-automated-ci-server:latest</br>

web url: http://localhost:4000/view/test

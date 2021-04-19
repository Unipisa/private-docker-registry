# Private Docker Registry
Private docker registry documentation [dockister.di.unipi.it](dockister.di.unipi.it).

## Usage 

### Push
```bash
git clone https://github.com/Unipisa/test-github-docker-registry.git
cd test-github-docker-registry
docker build -t test .
docker tag test dockister.di.unipi.it/test/test:v0 
docker push dockister.di.unipi.it/test/test:v0
```

### Pull
```bash
docker pull dockister.di.unipi.it/test/test:v0
```

### Login
```bash
docker login dockister.di.unipi.it --username a040515
```

## Installation



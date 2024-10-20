# Kubernetes

## Pre-requisites
- Install kind (kubernetes in docker)
- - run: brew install kind

- Create cluster using kind
- - run below:
- - - without a config file: kind create cluster --name=programmatic-ly --image=kindest/node:v1.310@sha256:53df588e04085fd41ae12de0c3fe4c72f7013bba32a20e7325357a1ac94ba865
- - - with a config file: kind create cluster --name=programmatic-ly --image=kindest/node:v1.31.0@sha256:53df588e04085fd41ae12de0c3fe4c72f7013bba32a20e7325357a1ac94ba865

- - - check config file in Basic folder

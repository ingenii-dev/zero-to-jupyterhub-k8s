REGISTRY=ingeniisolutions
REPOSITORY=jupyterhub-hub
VERSION=1.0.0

build:
	docker build . -t ${REGISTRY}/${REPOSITORY}:${VERSION}

push:
	docker push ${REGISTRY}/${REPOSITORY}:${VERSION}

build-and-push: build push

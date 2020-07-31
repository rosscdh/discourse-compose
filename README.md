# Discourse Compose


Built a new version based on the official launcher and reworked its internals so that its more dockerised


https://github.com/rosscdh/discourse-compose
which uses an image based on
https://github.com/rosscdh/discourse_docker/blob/feature/kube-version/samples/kube_web.yml

```
cat samples/kube_web.yml > containers/my_kube.yaml
./launcher rebuild my_kube.yml

retag the image to something useful push and thanks for coming then use the docker compose

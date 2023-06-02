
```shell script
docker run \
    -e ARCHITECTURES_REPOSITORY_URI=https://github.com/dimalusa/archi.git \
    -e ARCHITECTURES_REPOSITORY_BRANCH=main \
    -e ARCHITECTURES_REPOSITORY_PATH=res/gestion \
    -p 8080:8080 \
    mbouchenoire/lowfer:0.3.1
```
[![](https://drone.prakashprasad.com/api/badges/indusninja/docker/status.svg)](#)
# docker
Images that are useful for development projects:
- C++ development
- OpenGL graphics development
- Jekyll

## build image
```bash
docker build .
```

## tag an image
```bash
docker tag 0eb1929591c2 indusninja/jekyll:latest
```

## push to docker hub
```bash
docker push indusninja/jekyll
```
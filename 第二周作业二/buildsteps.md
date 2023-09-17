# 配置auth config

# add tags
docker tag go:test1 sofia123/test:v1
# push images
docker push sofia123/test:v1
# build images for multipul platforms
docker buildx build --push --platform linux/amd64,linux/arm64 --tag sofia123/test:v1 -f Dockerfile-1 .

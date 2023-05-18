# dockerTest
* 도커 빌드 스크립트
* 연습용

# Docker build
```
git clone https://github.com/nowage/dockerTest
cd dockerTest/UbuntuDocker
docker build --rm -t nowage/ut:v2 .
docker images
```

# Docker run 
```
docker run -it --name ut -v ~/df:/df --rm nowage/ut:2
```
